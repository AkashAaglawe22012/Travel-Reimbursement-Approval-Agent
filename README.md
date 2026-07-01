# Travel-Reimbursement-Approval-Agent

For running the code put cohere api key

"""claim = {
    "claim_id": "CLM1001",
    "employee_id": "EMP001",
    "travel_request_id": "TR1001",
    "submitted_date": "2026-06-30",
    "expenses": [
        {
            "expense_type": "Hotel",
            "receipt_file": "hotel_invoice.pdf"
        },
        {
            "expense_type": "Meal",
            "receipt_file": "meal_receipt.jpg"
        },
        {
            "expense_type": "Taxi",
            "receipt_file": "taxi_receipt.jpg"
        }
    ]
}
result = graph.invoke(
    {
        "claim": claim
    }
)

print(result)""" 
used this as sample input
