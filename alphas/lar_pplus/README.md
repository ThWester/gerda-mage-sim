# alphas/lar_pplus
**Remember to update also `UTILS/sim-parameters-all.json`**!

In this directory the simulations of alpha decays on the p+ contact and in the LAr close to the p+ are stored.

# simulations

| isotope       | contact    | primaries | software tag \[branch/commmit\]  | notes               |
| ------------- | ---------- | --------- | :------------------------------: | ------------------- |
| Ra226 \[all\] | K.v.Sturm  | 1e9       | ?                                | simulation V.Wagner |
| Rn222 \[all\] | K.v.Sturm  | 1e9       | ?                                | simulation V.Wagner |
| Po218 \[all\] | K.v.Sturm  | 2e8       | MGDO: `clhep_2.3.3.1/cece4fe` MaGe: `GERDAPhaseII-Dec2017/9fe03ca` container: `g4.10.3_v2.1` | |
| Po214 \[all\] | K.v.Sturm  | 2e8       | MGDO: `clhep_2.3.3.1/cece4fe` MaGe: `GERDAPhaseII-Dec2017/9fe03ca` container: `g4.10.3_v2.1` | |
| Bi214 \[all\] | K.v.Sturm  | 2e8       | MGDO: `clhep_2.3.3.1/cece4fe` MaGe: `GERDAPhaseII-Dec2017/9fe03ca` container: `g4.10.3_v2.1` | |
| Pb214 \[all\] | K.v.Sturm  | 2e8       | MGDO: `clhep_2.3.3.1/cece4fe` MaGe: `GERDAPhaseII-Dec2017/9fe03ca` container: `g4.10.3_v2.1` | |

# macros

The original files, macros and info by Vici can be found at mpik in /lfs/l3/gerda/vwagner/Simulations/AlphaSimPhaseII

## LAr p+

/gps/pos/centre               0 0 1.9895
/gps/pos/type                 Volume
/gps/pos/shape                Cylinder
/gps/pos/halfz                0.5
/gps/pos/radius               0.9
/gps/ang/type                 iso
