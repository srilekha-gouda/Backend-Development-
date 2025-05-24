->Mini Order System – FastAPI Project

This project is a simple backend system for managing customer orders, built using FastAPI and Python. It supports basic CRUD operations and a summary report, using in-memory storage (dictionary).

->Features

- Create new orders with customer and item details
- Retrieve a list of all orders
- Fetch a single order by its ID
- Update the status of an existing order
- Get a summary of total number of orders and total order value

->Technology Stack

- Python 3.8+
- FastAPI
- In-memory storage (dictionary)

->Setup Instructions

1)Install dependencies
pip install fastapi uvicorn
2)write a code(Visual studio)
3) Run the API server
uvicorn main:app --reload
4)The API available at
http://127.0.0.1:8000


->API Endpoints
1)POST /orders -create a new order
2)GET /orders -List all orders
3)GET /orders{order_id} -Retrieve a special order
4)PUT /orders{order_id} -update the status of an order
5)GET /summary -Get summary of all orders

Known Limitations
Uses in-memory storage, so data will be lost when the server restarts.

No authentication or authorization is implemented.


->License

This project is for educational purposes and part of a backend engineering assignment no specific license is required 


