``` mermaid
flowchart TD
 B(Interactive map- created using Leaflet)
    B --> C{Elements to consider}
    C -->|Data| D[- What quantitative data will we display on the map and why
- We need to consider why we are using a map in the first place- how does using a map further our agenda/ why is it the best suited approach to making our project?
- How to best display the quantitative data on the map- eg. potenetially a Heat Map? Where it goes red to green based on a certain criteria of rating]
    D--->|Organisation of geographic space| E[- How will we geographically distinguish the different areas of Newcastle
- Electoral ward boundaries? Or a more arbritary approach where we decide the mapping of areas
- Include points-based data on top of area data
- We need to consider a meaningful way of organising space/ reason as to why we are organising the geographical space in that way
- Do we include a zoom in/ out feature? If so, at what point should the data points aggregate together?]
    C -->|Pop-ups| F[- Will the qualitative data, the tenant submissions, feature on the map?
- They could feature as a pop-up, then be clicked onto for more detail]
    C -->|Filter options| G[-The quantitative data displayed on the map will depend on the filter options the user selects
- The filter options we use will be attained from the Optimal Workshop Survey results]
