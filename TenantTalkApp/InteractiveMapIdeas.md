``` mermaid
flowchart TD
 B(Interactive map- created using Leaflet)
    B --> C{Elements to consider}
    C -->|Data| D[- What quantitative data will we display on the map and why: Based on gentrification research, space will be organised by electoral ward boundaries and include average rental cost data per area as a way of showcasing which areas have experienced gentrification most heavily. This will provide indication of the impact gentrification has had on different areas of the city, which will give users insight into where they may want to rent based on the cost of that area/ affordability to rent.
- We need to consider why we are using a map in the first place- how does using a map further our agenda/ why is it the best suited approach to making our project?: the map is best suited to empowering tenants through being informative, giving them the knowledge and tool to make the best decision renting choice for them
- How to best display the quantitative data on the map- eg. potentially a Heat Map? Where it goes red to green based on a certain criteria of rating: Ideally we would like the areas to be colour coded to be visually different ]
    D--->|Organisation of geographic space| E[- How will we geographically distinguish the different areas of Newcastle
- Electoral ward boundaries? Or a more arbritary approach where we decide the mapping of areas. We need to consider a meaningful way of organising space/ reason as to why we are organising the geographical space in that way: electoral ward boundaries, and this is because it highlights the different areas of town accurately and effectively
- Include points-based data on top of area data
- Do we include a zoom in/ out feature? If so, at what point should the data points aggregate together?: the individual tenant stories will be visible when you zoom in, but when zooming out, they cluster together in one point to create an overall data 'story' for that area]
    E -->|Embedded into app| H[- The tenant stories themselves will be shown on the app]
    C -->|Pop-ups| F[-The tenant submissions will feature on the map. They will feature as a pop-up, then be clicked onto for more detail]
    C -->|Design| G[-The design of the map will be rigid and information as it deals with quantatative data
- However tenant stories on the app will be designed in more abstract, fluid ways of capturing experiences]
