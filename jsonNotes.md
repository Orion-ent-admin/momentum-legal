
When we make our first donation, edit the contributions.json file to be the following:

{
    "totalAmount": "$247.50",
    "nextContribution": "July 2027",
    "contributions": [
        {
            "date": "January 2027",
            "recipient": "National MS Society",
            "amount": "$247.50",
            "receiptFile": "receipts/jan-2027.pdf"
        }
    ]
}

After the second donation:
{
    "totalAmount": "$429.80",         - This changes to the total amount
    "nextContribution": "Jan 2028",   - This changes to next contribution
    "contributions": [
        {
            "date": "July 2027",               - New entries go at the top of the array so the most recent shows first
            "recipient": "National MS Society",
            "amount": "$182.30",
            "receiptFile": "receipts/jul-2027.pdf"
        },
        {
            "date": "January 2027",
            "recipient": "National MS SOciety",
            "amount": "247.50",
            "receiptFile": "receipts/jan-2027"
        }
    ]
}


When updating:
1. Clone to GitHub Desktop or Visual Studio Code
2. Add appropriate receipt pdf
3. Update .json according above
4. Commit and push changes
   4.1. If using GitHub Desktop and Visual Studio Code, make sure to confirm pending push in desktop.
   4.2. Confirm on web respoitory.
