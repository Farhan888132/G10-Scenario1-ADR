<a name="_wgnjikh4mzes"></a>Assignment: Architectural Decisions 

By: Farhan Batada, Sarah Tenebro  
# <a name="_76d9j8v04v5u"></a>Scenario 1 
## <a name="_kz4augolsv2z"></a>ADR: Platform
### <a name="_pi7jn20hvzm"></a>Status
Proposed 
### <a name="_r1q9ei4h06hb"></a>Context
The application requires syncing data with a web server.
### <a name="_q8tnm4xdkoye"></a>Decision
Hybrid App
### <a name="_lweo8z4bukt"></a>Consequence
This will allow for updating of data whenever an internet connection is available, along with use of most features running client-side in offline-mode.







## <a name="_rxus1or4ocwd"></a>ADR: UI Framework
### <a name="_b7ckxl3si9xu"></a>Status 
Proposed
### <a name="_xvklx66y9nod"></a>Context
Necessity of providing a seamless and user-friendly experience.
### <a name="_tm6sxfz65pud"></a>Decision
React/React Native
### <a name="_rbrv5rvbnm7"></a>Consequence
Developing a good UI design is made easier with the many component libraries built on top of the framework.

## <a name="_alqor9kbrns"></a>ADR: Backend Language
### <a name="_hqwo2vpb01ty"></a>Status
Proposed
### <a name="_ta5ojtzbafl5"></a>Context
The UI Framework that was chosen, React/React Native, uses JavaScript as the backend language.
### <a name="_eeng2vh14lqy"></a>Decision
JavaScript 
### <a name="_bbhskfk673tl"></a>Consequence
The integration between backend and frontend will be seamless.

## <a name="_ithrh8z8fee3"></a>ADR: Permissions
### <a name="_pyg2qwrn6ujo"></a>Status
Proposed
### <a name="_w2iuh8hcx32"></a>Context
The company wants to be able to send push notifications to their customers, allow the app to sync data with the server, and track their customers’ behavior.
### <a name="_swxhfc7kdwem"></a>Decision
Internet Access, Notifications, Device Internal Storage 
### <a name="_tt7sf78v8gq8"></a>Consequence
The aforementioned permissions are prerequisites for the features in the requirements, therefore, only with access to those functionalities can the requirements be met.

## <a name="_b11edolxz0on"></a>ADR: Data Storage
### <a name="_5g7ot9uafjoi"></a>Status
Proposed
### <a name="_l0962v6ipb1"></a>Context
The app needs to be able to have a database that is able to store and manage the data.
### <a name="_ggl8g12ot2em"></a>Decision
SQL(Relational Database) 
### <a name="_2fm293d9nh14"></a>Consequence
The relational nature of SQL allows a more efficient way to manage and retrieve data, increasing the app’s performance.
