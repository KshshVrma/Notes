declarative, pause , warmup, volume, framework, one though at a time
3 steps, 2 types 1 thing, point action result ask

Observer Pattern is a common pattern which follows a similar model to the publisher and subscriber, it can be very useful when we have a one to many dependency upon the objects, suppose you have a weather station which has to update multiple displays, now assume with every change in the weather station you would have to modify the displays to output the recent information , one way to achieve this is using the observer pattern, where we have a subject and observers, the observers request subscription to the subject and at runtime can remove the subscription as well the point is that the subject can store of list of observers and call the update method on top of them so that the changes can be pushed to the observers without any intrervention from their end. the subject should implement methods like addobserver removeobserver getstate updateState , and the observer should implement sometihng like update which can be called by the subject upoon any change, the benefit of this system is that the coupling between the classes is comparatively less, as the alternate would be hard coding the subject with all the observers which is not a good practice as the would result in a lot of modifications if any change is required, so instead we follow a push pattern where if the subject passes into any change then for all of the subscribed observers it can push the changes/ or trigger a pull by the observers so that they can make use of the latest values presented by the subject.

the xsd is the pattern which makes use of jaxb which makes the conversion of java object to and from xml format possible , the schema needs to be followed during such request.

when it comes to lld the solid principles are also very important which include single responsibility principle which states that the code should be written in a manner such that the classes are only used / modifiable in the future by a single stakeholder so that there are no unwanted implications of making any changes to the current code. The other principle is Liskov substitution principle which states that the signature of the superclasses should be replacable with their subclasses so that there is consistency between the implementation and any child which inherits has the implementation of the methods listed in teh parent . Interface segregation means that the interfaces should not contain the signatures that are not going to be used by a  lot of the implementations so it is a red flag if the interface has the methods which are not actually used by the implementations. The other are dependency inversion princple .

The Neetcode 150 can be used as a good intro as it covers a lot of topics and especially if the are coverd in about 2 months , can make the user confident of giving any inters ,so practice the main problems which include graph dp and greedy + bs/sw.

This week we can focus on : 
1 design pattern:
Strategy Pattern.

21 neetcode 150.
1 chapter from the hld system design book.
1 prototype of the lld questions.
extra:
continue on wibe coding if time permits.
Ai for the hack: check if we can make user of vertex ai/gemini to what use cases.
as scraping a 2fa site might not be as straight forward, however we can assume that we can have the data already present somehow and that might as well work.

struts are a framework which are normally used in legacy systems, especially with spring applications, the point being that they require some xml based configurations, we declare a struts.xml file where we declare the mapping between the jsp and the class which handles the actions.
the configuration file is like action> name =x path =x. now this path should contain the action class. the action class intern contains a execute method which normally contains all the logic ie it calls the service class which calls the dao class and so on..

apart from code copilots we can have hud's which do not interfere with the process of the work but are like invisible assistence we can compare and contrast using chatgpt vs using grammerly grammerly helps us without us asking and this can acttually be useful , so in general we have some use cases defined, for easy task we can take help of copilot but for advanced task hud's might be better.

applicaiton might take about 10 months so take that into account . 

Rate-limiters are fixed limits beyond which the system refuses to responde while throttleing is reduciton inthe response rate so that the request a full filled but in a slow manner, also debouncing is loading while the response loads.

Rate-limiters are normally present in the middleware layer or the server layer, depending on the usecasel.