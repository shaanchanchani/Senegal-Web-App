
### Overview:
This is a Geographic Information System web app developed for the Video Analytics for Understanding Animal Behavior research project at Purdue University. Our team is working to support a larger study investigating chimpanzee hunting behavior by interpreting data captured from motion-triggered camera traps in Senegal. The ultimate aim of this project is to provide primatologists with software to geospatially and temporally visualize prey abundance.

### Demo:
![](https://github.com/shaanchanchani/Visualization-Tool/blob/main/Demo2.gif)
*Demo gif may take a second or two to load*

### Setup:
Run the following script to install all the necessary dependencies
```
pip install -r requirements.txt
```
This program establishes a framework for dynamic information to be displayed when each site marker is selected. Callbacks are used to update the map interface in response to user actions. Session states are used to store user input and keep track of the state of the map across re-runs. Refer to the comments in the `map.py` file for a more detailed explanation for how these features are implemented in the code. For those interested in learning more, I found the [State management](https://docs.streamlit.io/library/api-reference/session-state) section of Streamlit's API documentation along with this [video](https://www.youtube.com/watch?v=5l9COMQ3acc&ab_channel=M%C4%B1sraTurp) to be useful resources.



### Task List:
- ~~Display Site Markers at each site~~
- ~~Display preliminary classification results for Baboons~~ 
- ~~Toggle Map View from Satellite Imagery to Topographical~~
- ~~Display Sample frames upon clicking site markers~~
- Swap Forecasted Weather API to Historical. Ensure Spatial Resolution of data.
