Risk Analysis Outcomes
=============================
.........

Peak Gust Wind Speed (mph)
---------------------------
.. figure:: figures/o_mph.png
   :scale: 25 %
   :alt: Logo


Damage State Probability (DS1)
---------------------------
.. figure:: figures/o_DS1.png
   :scale: 25 %
   :alt: Logo



Damage Ratio
---------------------------
.. figure:: figures/o_DR.png
   :scale: 25 %
   :alt: Logo


Dislocation Map
---------------------------
.. figure:: figures/Org_D.png
   :scale: 25 %
   :alt: Logo


Damage States
---------------------------
.. figure:: figures/org_dmg.png
   :scale: 25 %
   :alt: Logo
   

   >>> pressure.to_excel('pressure.xlsx')



Distance Calculation
---------------------------
.. doctest::   
   >>> r, pga, pgv, pos = Distance.com_pga_dist(node,ex,ey,M)
