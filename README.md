# interactivemap  
This interactive map was used in the app [https://offthecharts.vercel.app/locate]. At inception of the feature idea, the objective was two-fold:  
- data visualization : geographical breakdown of "assets" owned by [Sorare] users
- showcase how AI code-assistant can enhance a developer's capabilities / productivity  

## The javascript component  
This component was developed by PITTI, lifting a map created by Simplemaps.com (MIT License). All relevant information regarding the original Simplemaps.com map and how we processed it are presented in worldMap.js.  

## AI code-assistant : GPT-4 (state of the art at the time of writing)  
Notes for posterity: GPT-4 kept suggesting to download a third-party package, which was not the objective of this project as we wanted full flexibility on what data to pass to the map, and how to do it. The proposed solutions may have addressed the need for flexibility... but we will never know.    
GPT-4 did not provide a silver-bullet but it was not a complete failure as it did help a lot with the processing of the initial map from Simplemaps.com. The time saved by not trying to work out the regex on our own was probably worth the monthly subscription. And then, there is all the invisible support (never quantified) when it comes to debugging.  
Overall, it was certainly what we expected, but it did enhance productivity sufficiently to offset the monthly cost... 
