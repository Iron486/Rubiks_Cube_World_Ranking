# **Rubiks Cube World Ranking**

The dataset contains 3 tables:

- The first table (`events.csv`) contains the events that are ranked in the World Cube Association competitions (for instance, the `3x3x3 cube` is the classic Rubik's Cube, `4x4x4 cube` is the 4-layer version of the original one, `3x3x3 Multi-Blind` is the solution of multiple Rubik's cubes blindfolded ). 
- The second (`persons.csv`) one includes the people who participated in at least one competition, with their respective name, country, gender, ID and sub ID (the last one was created to avoid confusion among people who share the same name).
- The third table (`ranking.csv`) shows the world, the continental and the national ranking of the people for each event in which they participated (Note that the ranking is based considering the least-time resolution of the cube).

### **Collection methodology**

The tables were extracted from the following website: https://www.worldcubeassociation.org deriving from the 'results' tab. They were updated to the ranking of June 11, 2022. 

Moreover, the extracted tables were selected considering the ones with meaningful information regarding the ranking and some of the columns were renamed or dropped. Click the following file [rename_drop_WCA_data.ipynb](https://github.com/Iron486/Rubiks_Cube_World_Ranking/blob/main/rename_drop_WCA_data.ipynb) to take a look at the preprocessing steps.

