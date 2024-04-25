# Cheapest-Flight-Ticket-Finder (Updating)

This project aims to use related API to find the cheapest flight ticket from one location to another from tomorrow of current date to 3 months later, and format the result in a Spreadsheet.

## Example

Suppose we want to find the cheapest flights from London to other cities within 3 months:

[<img width="500" alt="image" src="https://github.com/ShiyuFan0820/CheapestFlightTicketFinder/assets/149340606/132f5c3b-dc2f-42af-97a8-e847c1dd3317">](https://youtu.be/3JmRTRkgSH0)


## Instructions for Use 

1. [Flight Deal Google Sheet](https://docs.google.com/spreadsheets/d/1ccQtFQE5aoiHjkyCRJJ4hPTghZLmrfm4bqOYlNipnrM/edit#gid=0), open this link, create your own Google Sheet acount and make your own copy of the starting Google Sheet, I already fill in some city names, you can change them to the city that you want to go. It should be noted that the `IATA Code` in the spreadsheet is **International Air Transport Association** code, which is a three-letter code assigned to the airport around the world, These codes are used for airline ticketing, flight planning, and baggage handling. They provide a standardized way to identify airports globally. But a city can have multiple airports, and here, I will only collect the city code, not the airport code.
2. Sign in to these API websites, you will use them in the code later.
- [Google Sheet Data Management -- Sheety API](https://sheety.co/)
- [Tequila Flight Search API Documentation](https://tequila.kiwi.com/portal/docs/tequila_api)
3. Sheety API
- Create a free account for Sheety API, and sign in with your Google Sheet account. Don't forget to open the access when signing in to your account.

<div align=center>
<img width="500" alt="image" src="https://github.com/ShiyuFan0820/CheapestFlightTicketFinder/assets/149340606/37a5fb5f-1a66-48d0-a0fa-94cd344f9b78">
</div>

- After entering your Sheety API account, create a new project from Google Sheets, and paste your Google Sheet URL in the place it shows you.

<div align=center>
<img width="500" alt="image" src="https://github.com/ShiyuFan0820/CheapestFlightTicketFinder/assets/149340606/bc07592a-3786-4e0f-980f-0c3f04d91609">
</div>


<div align=center>
<img width="500" alt="image" src="https://github.com/ShiyuFan0820/CheapestFlightTicketFinder/assets/149340606/28983520-46c5-4649-a395-e2846eb7f4d2">
</div>

- If you don't log in to Google Sheets and Sheety API with the same account, your spreadsheet can't be edited with Sheety API.

<div align=center>
<img width="500" alt="image" src="https://github.com/ShiyuFan0820/CheapestFlightTicketFinder/assets/149340606/6304a89f-5934-4e0c-8d9c-615c1bc173fc">
</div>

- Open all access limitations of your project in Sheety API, and then your Sheety API is all set.

<div align=center>
<img width="500" alt="image" src="https://github.com/ShiyuFan0820/CheapestFlightTicketFinder/assets/149340606/5b8bae34-6852-4343-8112-eb9f2f8aa066">
</div>

4. Tequila Flight Search API
- 






