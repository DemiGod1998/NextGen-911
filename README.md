# NextGen-911
Codefundo project built on idea of efficient management of aid resources to save lives and decrease economic losses during natural disasters.

#Planning to build :
     We are planning to build a software that could perform the following tasks during an event of a natural calamity :
     1. Reducing the congestion on the 911(or any such emergency service) server by using our app as a medium for people to contact 911           rather than manual calling that has to be individually recieved on the part of 911 station.
     2. Immediate aid requests can be send through the app as calling takes a lot of time and sometimes voice signals get corrupted during         such events.
     3. To check authenticity of request sent to 911 using many techniques like face and voice sentiment analysis.
        (In future our app could have a central server to filter requests on the basis of location clustering i.e. forward the requests            only if they are more than a certain number for a location.)
     4. Sending the request for aid to the 911 authorities even in case of "no signal".   

#How does it work :
    1. Using ML based facial and voice sentiment analysis system to confirm the authenticity of the request.
    2. Pulling out only the important words(i.e. location & type of the calamity and aid needed as asked by the user) and composing a            message from the input voice or text , which can be interpreted by the 911 authorities without wasting any time.
    3. Composed message is sent over a signal having the best coverage in the area at the time of calamity.(Just like our phone makes            calls even in case of no signal)
    
