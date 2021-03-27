For a movie ticket booking system, your design should provide features of ticket booking, show adding per day, validate limit for tickets per show, user services for different types of users, collection services should give data of all show collection average collection by show and so on.
	Goal:
1.	Implement a TicketBookingService, It should book tickets by show (No advance booking only same day booking).
Sample Interface:

public interface TicketBookingService {
	public boolean bookTicket(TicketDetail ticketDetail);
	…….you can add some more methods/behaviours.
}

2.	Implement a ShowService should say number of shows on same day for example 5 shows. Define related entities like ShowDetail.
3.	Per show there is a minimum limit of 10 and maximum limit of 30 tickets. 
4.	Every show should have price of it.
5.	Once minimum or maximum limit of tickets for show is reached then show can be completed.
6.	Implement UserService for website which could have types like customer, website admin. 
7.	Implement a CollectionService, which should have methods like collection by show, all shows collection and average collection by show.
