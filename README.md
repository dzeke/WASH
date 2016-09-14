#Systems Modeling to Measure Performance and Evaluate Management Alternatives to Improve River and Riparian Habitat Quality and Area

Managing river systems necessarily requires an understanding of the interaction between stream ecology and hydrology. The suitability of a watershed physical habitat to support the livelihood and productivity of its biota primarily depends on managing flow. Habitat conservation and restoration efforts require an understanding and a measurement of the spatial and temporal ecological response to alterations in flow regimes. Managers use deterministic and qualitative measures such as habitat quality indexes to measure ecological response of particular species at certain locations and times to flow alterations. I propose improving habitat management decision-making by incorporating habitat quality indexes as objectives to maximize in a systems optimization model. This **Watershed Area of Suitable Habitat (WASH)** systems model uses habitat quality indexes to measure physically-available suitable habitat. WASH also adds spatial and temporal functionality to quality indexes to recommend environmental flows for riverine, floodplain and wetland habitats while maintaining water for human beneficial uses. WASH also highlights promising restoration and conservation sites. In addition, WASH proposes and ranks alternatives for managers to restore and protect natural habitat. WASH formulation is generic and adaptable to other regulated river systems and for species of concern. I apply the model to the Lower Bear River, Utah to guide existing habitat conservation efforts, recommend water allocation and show tradeoffs between human and habitat use of the available flow.

##Objectives of WASH
* Quantify suitable habitat area within the watershed by embedding habitat quality indexes in a systems model, and
* Identify strategies to allocate scare natural (e.g. water) and management (e.g. financial) resources to improve habitat quality.


##Watershed Area of Suitable Habitat (WASH) 
WASH recommends management strategies to allocate scare natural (e.g. water) and management (e.g. financial) resources to improve habitat quality. The model maximizes available and ecologically suitable area for species of concern by timely and spatially allocate water to riverine, floodplain and wetlands habitats subject to natural, physical and management constraints. WASH embeds habitat quality indexes in a systems model to: 1) quantify available and suitable habitat area within the watershed; 2) quantify the interaction and linkages between water-demanding watershed components such as riverine, floodplain and impounded wetlands habitat; and 3) represent temporal and spatial variability of an ecological system and prioritize species of concerns to managers. The selected species and habitat attributes can change from one river to another. Therefore, the model formulation approach is designed to be generic and transferable to other regulated river systems. Following this approach, WASH model formulation accepts the addition (or subtraction) of habitat quality indicators and species. WASH is designed for decision makers with the ability to prioritize reaches, seasons, environmental users and species. 
WASH systems model maximizes a single composite performance indicator to represent habitat quality. This indicator is refer to as WASH and is measured in unit area (Mm2) as a quantitative measure of the area within the watershed that is both physically available and ecologically suitable to support species. Mathematically, WASH quantifies habitat suitability based on the level of existence (or lack) of the hydrologic and ecological habitat conditions required to maintain the livelihood of indicator species. For example, river water depth required for fish species and flood recurrence for floodplain vegetation recruitment. WASH is composed of the weighted sum of three sub-indicators representing the three main foci of watershed: riverine, floodplain, and impounded wetlands habitats (Figure 2). Each sub-indicator measures the suitable area, measured in unit area, for its respected habitat. The value of each sub-indicator is calculated by multiplying an affected physical area by a suitability index that takes a value between 0 (representing poor habitat conditions) and 1 (for excellent habitat condition). 

We embed the WASH performance indicator in a system optimization model that measures the cumulative ecological response of species to alterations in flow. WASH maximizes suitable habitat area by adjusting flow-dependent decision variables such as reservoir releases and diversions. The optimization is subject to constraints such as infrastructure capacity, mass balance, water availability, and budget for management actions.  We code the optimization model on the General Algebraic Modeling System (GAMS; Hozlar 1990) and run it to recommend the allocation of water and financial resources that maximizes habitat quality as measured by the WASH indicator. 


