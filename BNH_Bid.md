# Bid for Building New Hope Custom Map Creation

## Proposal
The document serves as a bid to fulfill Building New Hope's request for a custom map to embed in their website. We have belive the project to take 5.25 hours to complete. At a rate
of $100 per hour, this project is estimated to cost $525.

### Breakdown of Tasks

- **Generate a Custom Pallette**
  - Building New Hope's Logo will serve as the source for colors that will be used in the map design. We will upload an image of the logo to ChatGPT and
    prompt it to generate five colors that can be used to design a map based on what we have uploaded.
    
- **Build Map Using Google Map Styling Wizard**
  - The color pallette will then be applied using Google's Map Styling Wizard to make edits to an existing map. We will start with the Retro theme and then change colors
    for the labels and geometry of Country, Province, Land Parcel, Points of Interest, Road, and Water feature types. Modifications to feature subtype colors will also be made
    on a case by case basis.
     
- **Documenting Design Elements**
  - A look-up table detailing the modifications to all feature types will be created. Building New Hope will then be able to easily make changes if they are deemed necessary. 
  
- **Making Map Embedable**
  - We will then convert the modified map to JSON format making it easily to download and to place into an existing website. 

- **Creating Instructions to Utilize Map**
  - Breif instructions on how to utilize the provided JSON file will be included.

### Cost Estimation Breakdown
<img width="791" alt="Screenshot 2025-03-27 at 1 21 43 AM" src="https://github.com/user-attachments/assets/af273180-6f36-490f-a228-9d246b5b8f2b" />

## Products
### Palette (Inspired by Logo):
<img width="150" alt="image" src="https://github.com/user-attachments/assets/4b6a5c9b-398b-4ca8-ae80-e419060237ea" />  

- Lime Green (#B5C700)
- Golden Yellow (#E5A823)
- Sky Blue (#24B8D4)
- Deep Coffee Brown (#6F4E37)
- Soft Aqua (#76D6D2)

### Lookup Table:
![image](https://github.com/user-attachments/assets/97cc9d69-7f50-4484-bfab-e93c8d22e5f6)

## Samples
### Region View
![Picture1](https://github.com/user-attachments/assets/f52f033a-a064-4968-98e3-18af8edd179e)

### Metropolitan Area View
![Picture2](https://github.com/user-attachments/assets/6985ccc2-a43b-47c9-840a-c5eaf0c366a9)

### Street View
![Picture3](https://github.com/user-attachments/assets/8e3dbc8d-9231-4f0e-bef0-39044b7908b6)

### Access to JSON File
The JSON file for this map can be obtained by cliking this [link](https://msecomandigis.github.io/gis-portolio/BNH_Map.json).

## Directions for Use
In addition to downloading the JSON file, you will have to obtain a Google API key in order to embed it in your website. Once you have both of these elements, follow this 
[link](https://github.com/OpenGlobe/portfolio/blob/master/sample_google_styling_wizard_template.html). Modify the file by pasting the API key where it says "YOURAPIKEYHERE" and 
replacing the style section with the JSON code. You can then paste the code into your website to embed the map.


