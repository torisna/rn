# rn
research note

#make grid files
xyz2grd.sh
 please change GridInt and awk positions


#STCM analysis---------------------------------------
based on STCMkit.
this codes are for the support to use STCMkit.

1 aori-workflow/
->02_AORIstcm_cat.sh
->STCM_milisec_v4_8fig.m
->stcm2stc.m
->anmd2rel_v3.m

2 kobe work flow/
kobe data need to supply proton and depth data
->format_stcm_v2.sh
->depthget.sh #gmt (
->proton_get.sh  (we get *dat.matd data)
->STCM_milisec_v4_8fig_kobe.m
->stcm2stc.m
->anmd2rel_v3.m

3 Check data/
->plot_topo_anm.m
->emag_map_pub.sh #gmt
 and EMAG2_nise.cpt #gmt
