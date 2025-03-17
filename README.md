# Scheduling
Key Points

I sort WIPs by ascending Q‑Time.  
For each WIP, consider pairing it with another “not yet scheduled” WIP that might ride on the same cart if it doesn’t violate either WIP’s Q‑Time.  
check two sequences for 2-WIP trips:  
Mode A: PICKUP–DELIVERY–PICKUP–DELIVERY  
Mode B: PICKUP–PICKUP–DELIVERY–DELIVERY  
choose whichever yields (a) no violations and (b) less total travel distance.  
If no pairing is feasible (or pairing is worse), deliver the WIP by itself.  
