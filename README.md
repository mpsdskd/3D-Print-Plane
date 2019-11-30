# 3D-Print-Plane
Mostly 3D-printed flying wing

# Construction ideas
- Manufacturing technique fixed as FDM
- Restrictions of FDM:
    - Fixed maximum size: ~190x190x190mm³ bounding box
        - Wing needs to be printed in parts, parts need to be connected stabily
    - Highly anisotropic material -> Parts brittle perpendicular to layers
    - Rough surface perpendicular to layer lines
        - rough parts approx. along airflow
    - "low resolution" in z (-> Layer height)
        - Wing must be printed vertically with layer = xy-plane
    - ~~Reinforcements can be made by constructing very slim Cuts into the model. On Both sides of the cut the Slicer will create wall lines, thus adding additional plastic in places needed ~~
        - ~~Useful with reinforcemnts for wing spar, and screws~~
        - ~~Creade ribs by making a cut through the wing~~
    - Reinforcements: 
        - Parts in CAD are solid and should in general be printed as hollow -> no infill, wall thickness one line
        - Reinforcements (Ribs, reinforcements for screws) are designed as solid parts as well, exported as 3d meshes and used as infill modifier meshes in your favourite slicer
    
- Maximum lightweight design
    - <500g for personal insurance purposes
    - ↓weight -> ↓Sinkrate
        - useful for (dynamic) soaring
    - just because
    - How to achieve this with FDM?
        - Build hollow
        - Low wall thicknesses -> 1 trace
        - Rigidity & form stability still necessary for aerodynamic shapes
            - Wing ribs, reinforcements necessary at important positions
        - Spar as structural element from Aluminium or CFK
        
    
- Aerodynamics
    - Flying wing
        - ↑ Efficiency
        - Challenges:
            - Equilibrium of Moments
            - Adverse Yaw
            - Yaw stability
            - Controlability
            -CoG
        - Elevons
        
- General ideas
    - Modular construction 
        - Just print new, whatever broke, not the whole thing 
            - Parts must not be glued, but screwed together
            
