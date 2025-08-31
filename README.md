# ORCA_TOP---Physical-Design-project-

1.This project implements the **ORCATOP Module ** through a *ASIC physical design (pd) flow.
2.It is focused on learning and practicing industry-Standard backend steps like Floorplaning,Placement,clock tree synthesis,Routing,sign off.


1.Floorplan:
    - The floorplan is created using ICC2, defining the chip's physical boundaries and pin locations.
    - The floorplan is optimized for minimal area and congestion.
2. *Placement*:
    - Standard cells are placed using ICC2's placement tools, optimizing for timing, power, and area.
    - Placement is done in multiple stages, with incremental optimization and refinement.
3. *Clock Tree Synthesis (CTS)*:
    - A balanced clock tree is synthesized using ICC2's CTS tools, minimizing skew and ensuring reliable clock distribution.
4. *Routing*:
    - ICC2's routing tools are used to connect the placed cells, optimizing for timing, power, and congestion.
    - Routing is done in multiple stages, with incremental optimization and refinement.
5. SINGOFF:
    - The design is verified using ICC2's physical verification tools, checking for DRC (Design Rule Checking) and LVS (Layout vs. Schematic) compliance.




##FLOW STEPS:
1.Import netlist,constraints (.sdc),Library files(.lib.
2.Floorplan (define core and die area,port placement,voltage area,macro placement).
3.Placement(Standard cells placement and optimization).
4.Cts(clock tree synthesis).
5.Routing(Global and detailed routing)
6.sign off(fixing Eco)





RESULTS:
-we achieved timing closure with WNS=-0.05ns and TNS=-0.88ns across all corners. 
-Optimized design with Utilization =0.7323.



##License

This project is licensed under the [MiC License ] (license).

You are free to:
-use this Project for personal,academic purposes. 
-Modify and redistribute it with proper attribution. 

Limitations:
-No warranty is provided. 
-The author is not liable for any damages.
