# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
[https://YourDirectionsApiURLGoesHere](https://maps.googleapis.com/maps/api/directions/json?origin=386+367,+Side+Rd+20,+Mono,+ON+L9W+6V4&waypoints=207219,+ON-9,+Mono,+ON+L9W+6J1&destination=Fleming+College+-+Frost+Campus?departure_time=1687906800?&mode=driving?avoid=tolls|highways&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE)
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJbSJ0-OxVKogR6XXQpJg9sbk",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "EiwyMDcyMTkgT04tOSwgT3JhbmdldmlsbGUsIE9OIEw5VyAyWjIsIENhbmFkYSIyEjAKFAoSCYcqBWZVACuIEUWvQF4MjVolEPPSDCoUChIJbbg9YvvgKogR2Yl7aNxWyis",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "partial_match" : true,
         "place_id" : "ChIJq6p6ZumM1YkRwlenRs5y5SY",
         "types" : [ "establishment", "point_of_interest", "university" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 44.3420667,
               "lng" : -78.7394659
            },
            "southwest" : {
               "lat" : 43.91919,
               "lng" : -80.1239585
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "16.1 km",
                  "value" : 16149
               },
               "duration" : {
                  "text" : "14 mins",
                  "value" : 854
               },
               "end_address" : "207219 ON-9, Orangeville, ON L9W 2Z2, Canada",
               "end_location" : {
                  "lat" : 43.928605,
                  "lng" : -80.05485569999999
               },
               "start_address" : "386367 Side Rd 20, Mono, ON L9W 6V4, Canada",
               "start_location" : {
                  "lat" : 44.0296892,
                  "lng" : -80.1127152
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 949
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 44.0270361,
                        "lng" : -80.1239585
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eSide Rd 20\u003c/b\u003e toward \u003cb\u003eON-10\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qpvkGn_~gNNlAHn@Jn@Hn@Hn@Hn@Hn@Hn@ZfCL~@J|@\\xArAxDVzAjApJnA~JfAnITpB"
                     },
                     "start_location" : {
                        "lat" : 44.0296892,
                        "lng" : -80.1127152
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13.0 km",
                        "value" : 13041
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 647
                     },
                     "end_location" : {
                        "lat" : 43.91919,
                        "lng" : -80.0772841
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003eON-10\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_`vkGve`hNpDk@|HoApF{@bS{ClCa@rEq@~HmAxCc@x@MfAQ`@GfAQb@GxGcAlFw@tB[`@Gb@IzIqAlAQb@GlFw@vCc@zCc@v@K|AQvCc@pCa@@AtAO~C]xAQr@IlBWxASLCr@KhBWbBYhB[TChCg@b@GnDq@dAQhB[b@I\\GjASHAlCc@~AY`@GvCc@lF{@b@G~@OvF_AdBWHAxFy@lAQnKcBrJyA~@OfJuAp@KzAUvF}@hBW?AxFy@`@IF?`BYjBYr@Kt@M`@GjBYtF}@bJuAjCc@~Cg@`BWZEbAQzAU`AOf@Kl@IDAf@Iz@MbAQdAQHAl@K~@O^GJAjASdAQb@Gd@If@Il@Kf@GXGVEPCPCREPCJAPETCHCJAJCLAJCRCLCHA@APCLCD?TEl@Ih@K`AOZGd@GXGHATCVGXE^G`@GBALC\\E^GXGZEh@I\\G`@G^G\\Gl@K\\E`@Id@Gb@ILC`@GHAZGRCPEZEb@I@?h@I\\GZEVE`@Gz@ObAOXEz@Op@Kf@Id@G^GVE^E\\GXEXEZG`@Gf@Gj@Kb@Gl@Kr@KFAl@Ip@Kl@Kz@Kl@Kt@KjAQt@M~@Oz@MjAQ`AOd@GJCbAOt@Mp@In@KRE^G`@GVEzA[bB[h@Kl@KHAj@Ih@Id@IlCc@`Ca@hB[v@MrAUZE^IzDo@b@IXEtAWxDm@fDi@`C_@hBYd@GjCc@pASp@KbB]h@Mz@SRG^MlAi@b@SV@@?@AvA_Ah@_@rAqAl@m@`AuA?AHWZk@\\o@Zk@j@mA`@{@Vk@h@cBv@aC`@wAtBkHnB_H^mAp@sBN_@Rc@b@_Ar@oAFIf@o@h@q@lAmAt@u@zDuD^]pCoC\\[nCkCLMhE{Dr@o@d@e@\\_@b@g@dAmA~@mAjBoCLQTG@CZe@vBmD`AsBVg@j@kA`A_C~@kCLc@z@qCrAcEh@aBx@}BXw@"
                     },
                     "start_location" : {
                        "lat" : 44.0270361,
                        "lng" : -80.1239585
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2159
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 147
                     },
                     "end_location" : {
                        "lat" : 43.928605,
                        "lng" : -80.05485569999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eON-9 E\u003c/b\u003e (signs for \u003cb\u003eNewmarket\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}}`kG~awgNUUw@{@_BcB]c@uA{A[]MMUYyBeC_@e@AAmB{BcAmAc@g@_@c@yBmCsAcBi@u@MQU]Sa@IO_@s@[q@Yu@Uo@IWKa@CMEMSy@CMG[E[ACG[GY?AG_@Mw@?ASqAGg@CMCQAIQuACWKo@]eCq@}Ei@{Di@cEUeBk@eECUU}AiAsIKo@MeAU}AGc@g@uDIo@U_B_AiH"
                     },
                     "start_location" : {
                        "lat" : 43.91919,
                        "lng" : -80.0772841
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "126 km",
                  "value" : 125943
               },
               "duration" : {
                  "text" : "1 hour 47 mins",
                  "value" : 6416
               },
               "end_address" : "200 Albert St S, Lindsay, ON K9V 5E6, Canada",
               "end_location" : {
                  "lat" : 44.3410364,
                  "lng" : -78.7416585
               },
               "start_address" : "207219 ON-9, Orangeville, ON L9W 2Z2, Canada",
               "start_location" : {
                  "lat" : 43.928605,
                  "lng" : -80.05485569999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "39.8 km",
                        "value" : 39801
                     },
                     "duration" : {
                        "text" : "29 mins",
                        "value" : 1765
                     },
                     "end_location" : {
                        "lat" : 44.0324381,
                        "lng" : -79.5796239
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eON-9 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wxbkGzurgNOeAq@{ECWa@uCEYCQWcBiAmIs@iFi@}D_@iCi@uDc@cDc@{C]eC_@eC]cC_AkGGi@Ic@Io@M_AESWiBCOG_@YmBM_A}@_GAKeAcHSyAE[[{BMw@OgAIq@{@eGYqBsA}JoAaJQoAWeBo@kE[sBm@aFWyBKcA]iC?E_@oCqA}JeAoIOmAi@eEi@eEa@}CUmBQsAIm@Io@Ks@CWa@cDACAMGa@QwAUgBGk@Ks@g@_EQ{AACc@oDWmBU}AIo@Iu@[}B_@mCcAqHQyA?CCSm@mE}AgLY{BE[g@gDg@cDOgAQeAOgAQeAOgAg@cD?AKo@Im@Km@OcAs@yEU_BKq@a@mCIm@UuAKw@Ie@AIGe@AGW_BSuAKw@WcBKo@i@yDm@eEU_B]eCIm@U_Bk@{DOiAEUe@iDIi@EYM_A[}B?AM_AW}BCQCUa@kDaAiIWwCGs@OyBEy@IeAI}BASA]MeEG}B@k@Ay@IaEEmBGaCGwBCa@EoBQiE[yEAKAUCS?EAEGq@KeASqAQy@Sy@EU[aAMY]{@m@mAaBgDaDsG]u@Wo@Yy@W{@[mAScAAEQeAM}@K{@Gw@Ca@CU?GGiAKeDAG?QEu@KsAo@uEqAoJc@iDGc@i@mEEc@]{B_@wCE[Kw@Ks@SoAS_BS}AQmAMw@aAuHCOcAsHUiBg@uD?CS{AEWCUUaBCW[}BQkAS}AYyBIk@QsA]oCQwAQqACMa@_Dw@iGSoAs@gFQyA]oCIk@AEAKqAqJ{@mGAQg@mDE[_@sC_@sCIi@OeAo@aFE[E[ESE[WsBe@iDGa@AM[_CCOQqAS}Aw@aGeAqHy@uFo@iF?Eq@yFc@aDOcAAIs@kF?AcAwHEScAyHo@uEw@}FOeAUiBQuAKm@Is@g@wDc@gD[yBEYWmBEa@QqAYyBIo@Io@UgBs@iFQwAa@uCGk@u@yFgAkIKu@q@iFs@oFgAkIWsBOkAGc@AKGc@i@_E[aCwAcKuAaK_@mCi@kEAICSEU?E_@oCWsBKeAAGSyBCOGs@U_DUkDCYEo@CYQeB[oB}@cFk@gDk@}CKk@Y_B?EWaBa@qCgA}Ic@gDS{ACUYuBa@}Ce@cDgA}IWeBSwAOgA_@mCQkAGg@M_AGc@w@kFa@eDWgBa@}Ci@aE_@iCa@}Cs@oFIo@Io@COyA_LM_Ag@wDe@uD_@oC[cCe@oDo@wE]oCAI]cCEYe@mDq@gFiAsIe@cD[{Bg@iDWcBIi@cAcH]iCo@aFYcCg@_EEa@CMSkBi@gEEYW}BS}AKy@e@aD_@wC_@kCYqBIm@_@mCIm@_@mC?Cc@_Dg@kDU}AIq@a@mCAMAAs@gFIw@M_AAOa@aDE]Gg@UgBEg@Io@Gi@Gc@EY[qCUkBEc@AAEc@UmBAKAEY}BIw@Ge@CS]oCE[]uCIi@QqAEa@OaAAMIe@]{Bo@}Cg@kCc@{Bg@kCo@sCk@kCe@_Ce@aCUoAUqAK}@CKI{@KiAWaDi@mGQkCAKEc@QoCIaAIs@Gq@SqAUaB{@cG[cCKw@QoAiA{Hu@wFm@oEm@_Ea@aDeBeNIm@g@_Ea@}CCSyA{KQwAIo@My@Y{BKu@KaAe@uDa@sCU}AS_Bw@iGAIWkBg@_EEYYuBIo@OiAIk@EWIo@s@eFM{@S_Ba@eCIk@e@sCMs@c@cC?CKs@[mBKs@EYo@eESwAUaBAGGc@_@sCIk@?AUiBQoA]oCMiAo@cFIq@Ky@QuAWiBeAmICMEa@YuBw@kGSyA[gCs@oF{@aHQoAcA{HM_AS}Aw@aGm@yEU_BIm@Io@S_Bg@{Dw@yFYuBAKAKAE}@yGGc@Q{AWoBGa@a@}CQkAM_AE[c@cDKo@Iq@_@mCg@aE]eCAIAOCKk@uEYwB_@oCU_BKy@Is@a@qC_@yCc@gDQgASaAc@eDYcCCQKi@a@eDc@gEQkAIg@Ky@QuAACK}@o@gFa@{Cc@kD_@qCWuBUaBY}BeAaIu@}FIo@qA}JGc@e@mDa@gDQmA_@oCMiAIo@qAuJYyBO_AKy@u@mFIo@c@_DwA_K[cCAG]iCAEe@oDc@_Da@uCUaBu@_F{@eGAGU{A{B}OYkBi@uD]aCkA_IcA{He@qDMy@gA{HK{@WcBIs@YqBa@yCm@uEE]s@gFk@gEo@}E[{BIo@U}AOeAWoBKo@aAyGUwAcA}GaAmHi@}DYoBM}@q@cFAKe@iDOmA_@kCe@mDCIuA}J?k@Gc@M}@cAsH_@mCc@eD[_Ci@aECQMq@EOIUy@sFq@uEcA}GSkAiC{O[mBKq@UqAcA_Iw@uGQ{AwAsL_@oDO_BAOKuAc@qH?CEq@KuAG}@CQKkAYsCKs@Q{ACS?AKw@k@wEM}@QyAc@wDE_@QuAMcACQq@}EM_AOkAS{A[eCmCsSc@aDGg@a@uCMgAy@qHIeAa@_DUkBc@aDYaCMy@?AIg@WuBm@uEe@uDAMOoAWaBEYIo@K{@Q{ACU_@mCGc@o@wEm@yEWoBQgBc@sD[aC_@uCe@cDQmAGg@EWK}@QmAOcAQeAW}AO_Ac@iCa@uBMu@AGKg@g@kCCo@?IAIYiB]qBmAsH]wB[yBQgAQaBAUCUS{AGc@g@mEIa@GYIY]cDO_BCWYqCO{ASiB_@iDOmAAOScB[mCE[WsBEWg@uDAGG_@o@uEG]m@mEs@qF"
                     },
                     "start_location" : {
                        "lat" : 43.928605,
                        "lng" : -80.05485569999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.6 km",
                        "value" : 8622
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 532
                     },
                     "end_location" : {
                        "lat" : 44.0554541,
                        "lng" : -79.477251
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eDavis Dr W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 31\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wawkGr{udNAGa@gDYmBq@_FM}@]_CQqAYmBAMIe@CUc@eCi@_EIo@Ko@U}AIo@U_BIo@Io@U_B_@mCG_@Gi@COKq@M{@OkAMw@i@yD?i@?Eo@sE]yBEY]}BU{AAA?AIe@o@{DKo@aAiGi@iDGSQW[gBO_AQeAY}A[gBc@kCKq@i@yCgA}H]kBa@sCO}@g@cF[wCWkCGi@m@oGOsAg@oE?ACWkAeJAIeA}Gm@aEA?E_@]qBIi@c@uCU}AAIa@eCiAeHoAcHm@gD[gBG[]kBi@wCW{AIq@Ii@G{@Ek@?EGgAA[Ak@CiA?E?q@?G?m@@_B@c@FyBDcCBiA?K?i@?}AEeAAc@AKUuCGm@a@cEGo@{@wIk@mFKs@]uD{@aFO_Ac@eBGUYgAeAiDCIO]ISu@gBSg@IQ_@_AUe@k@oAIQMWQe@e@mAAEQk@KYq@mCAIKo@U_B]cCCOSqAk@}DIc@S_BeA}HGc@EUUcBS_BM}@a@oCGk@S_BCW]eCa@mC_AwGq@aF}@_HgAkH?e@?SGi@Ky@UcBk@sEIo@G_@Ks@k@yDo@qEU}@}@yGe@qD@M?I?GAQ_@cCe@gDa@cDSoAMeASaBIq@S{AU_BIs@]oCCUEYAMq@mFc@qDCQQmAM_AQgBK{@S_B_@_DO_AM}@Ig@EWWiBGm@e@iDYaC"
                     },
                     "start_location" : {
                        "lat" : 44.0324381,
                        "lng" : -79.5796239
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "31.3 km",
                        "value" : 31267
                     },
                     "duration" : {
                        "text" : "31 mins",
                        "value" : 1850
                     },
                     "end_location" : {
                        "lat" : 44.1398003,
                        "lng" : -79.1037992
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eDavis Dr\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 31\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Davis Dr\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "qq{kGx{adNGa@EYeAsHc@kD]cC]cCU_BS}AIo@_@oCm@cEWgBCSKo@]gCWeBKo@U}AWoBg@qD_@uCi@}DCM[{B]mCEUOaAE][cC]cCw@sGOwAYsBE]E[Ko@CSIg@G[Mg@Q_Ae@oCCOWaBK_AKw@Q_BYgCIq@Im@Mm@COMw@MgAQoAQ_BWsBa@mCWgBc@{CaAiFCQI]i@qDCYG]EYc@cDg@yDIw@Gi@COMw@]yBWsA_@gCWiBQoAAO_@kCcAwHq@_F]mCk@yD_@oCiAmIG[O}@a@iCAE]mCCKCQi@yDCMMy@a@yCSqASyAG_@OoAESU_BMy@S}A[aCc@}Cu@mFa@_Di@aEaA}G[cCAI]cCS_Bo@sE_AiHQmACOIo@U_B]}BOkAAGCEGQoBeOiAkI@e@o@uFUmBCUQkBE[w@qFOeAQkAE_@i@oDg@wC]yBcAyGOaAa@iCqAyIy@aG]_CIk@i@qD[uBo@iEK[Mw@w@mFS}Aa@qCG_@E[a@oCqA}ICOeC{Pi@iDM{@EWOgAKo@a@mCw@cGSqAe@wCCQKs@Gg@[yBWgBo@yE]iCmAgJKq@?Ga@qC]oCiAmI{AaLGe@iAeIYqBKq@gAeIi@wDy@_GESgAaIoA{ICSCOg@mD[sBKq@q@aFuByNCQkDkVCMa@oC_@mCc@_Ds@cFWiBoAgJgA}HU}Aa@mCu@eFAGc@{CMaAOcAq@iFYkBu@kFo@qEg@mDUyAGa@Gg@Ig@SqA_@mCCMGe@Kk@Im@AESyAKm@qB}MM_AQiAACKy@SsAKs@_@kCIg@OaAGc@Ga@]iCCSEUs@cF_@iCScBSqAAMOgAOgAEUYsB_@mCE]CQOeAKu@Ii@AEIi@?EACQuAE[EYGi@AAo@cFAIAES_BG_@M_AAMIo@Ga@M}@?AG_@CUOiASyAUcBUiBKo@ScB}@{GS{A?EQgAKw@Kq@SqAWiBKo@AG?AO}@EWKu@ACIk@CUQiA_@gCAEk@}DEWEWGg@Mw@Im@UyAKu@UwAu@cFc@wCIo@oAkIa@oCyAcKu@kFQkAYqB_@oCaA}GwA}J_@qCc@uC_@gCu@mFw@mFs@cFCK_A}GKo@Io@Ga@M{@g@sDCKyB{O[yBOaA[eCKm@Io@U_BIo@U_Bi@{DIq@Im@AAi@}D?AIo@U_BIo@k@}DsA_Kk@}D_@oCGk@ACGi@YoBO_AMaAIo@_@oCWuBEYa@mCIo@QkAQmAQsAE[U_B]cCG_@c@}CAOSqACYACCUWiBm@mEg@sDWsBe@oDUaBKo@_@qCSaBKq@k@eEcAuHAMQiAIo@Im@AGIg@Gi@AEGa@AMAGIg@Io@QmAc@cD_@iC?Ai@eESyAESE[Iq@Io@Kw@OaAMcASyAS_BUeBACGk@Ko@Im@?AIo@Im@?AIo@ESGa@]gCAI}@uGIo@?A_@sCCUCSAGIi@a@_DEYUcBGa@AMKm@Mu@Gi@COIq@SwAQuAIo@EWAGCQE]COEYCUCSCQSiBIo@ACIk@Io@M{@WaB[_CKo@Io@U_B_@oCIo@U}AIo@CSE[Ko@Io@Io@Io@Ko@Io@Io@Io@Ko@i@_EKs@Gk@Ko@CQ]oCG[WsB_@mCOiAc@eDe@gDiAoIOgACWe@eDCYEU_@oCIo@EYCUYwBEWU_BIo@CUKo@UaBOgAOiACUg@mDCQE]a@qCAMGa@CMIo@u@oFE[cAqHEWEWCUKo@UcBCOIo@S_Bs@oFSuAAIGe@_@oCAIIo@{@uGAGg@wDa@uCq@_FAGAIe@iD}@yGCOu@kF?CGa@g@oDE[Io@EUOiACQQmAMcAQkAi@}DCSQkACSE[MaAQmACQo@}ECQQmACQo@{EKo@CSeA{HsA}Js@oFm@yEEUIo@EYCW]qCIm@Io@Gi@Ku@SyA?E]oCOcAC[Ko@Io@i@eEGg@i@cEE_@Kw@AGWqBU_BS_BU_BIo@Io@Ig@Is@G_@CSSwAYuBQkAACM}@QmA?CKo@AIQoAACIo@Gc@AGKs@Gc@AGKs@_@iC?CGe@Mu@?CGe@CIE[COIo@ACAKSmA?CG_@AKAC?CGa@AIa@iC?CIk@Ks@Ik@ACIo@Ii@AC_@kCACOeACUACKq@Ig@?Ca@sCWcBaCsPAGu@mFSwAa@sCACi@yD?CIc@AKOeAEYGe@AIG_@CO_@mCAGSwAk@}DM{@YoBMcAKo@AEGg@Mw@SwAIo@Ko@AEGi@U}AKo@?EKo@_@iC?EKo@U_BIg@Ku@Gi@G[U}AIo@CSKo@Io@G_@COE_@COG_@CO[}BKo@COGg@AGSuAAIAI_@eCCQe@kDESE[CSQiA?Ai@{DAAIm@UaBIm@AAM}@_@kC]aCIq@CME_@COG_@Ig@OgAIm@EYCWKm@?CIk@Ko@?CSuA?EKo@Io@?AUcBIg@Iq@CQSyAa@sCE]QoAWmBM{@Gc@MaAg@mD?CIi@QmAE[SuAM{@UcBWmBCOS}AM{@Ge@EYWmBYkBIi@E[E]Ie@Iu@COES?EKo@YsBEYGg@AG[}BMy@?GIg@Gi@CMGe@Mw@?CQsAAGU}ASyAKw@YkBOiAWgBE]OcAAEM}@?CIi@QqAQmAEYQmAg@gDEUEYGe@W}AWiBa@mC"
                     },
                     "start_location" : {
                        "lat" : 44.0554541,
                        "lng" : -79.477251
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.1 km",
                        "value" : 8118
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 354
                     },
                     "end_location" : {
                        "lat" : 44.2101141,
                        "lng" : -79.125647
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLake Ridge Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 23\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w`llGv}xaNiA^_Bh@q@To@RqA`@w@V]LaA\\i@PA?_@Le@N_AZm@RSHA?eCx@A@mBl@eEtAeBl@a@Lc@Na@LOFs@TcA\\A?A@cBh@IBYHQFoA^qBl@_AZ_@JSHa@LODs@TE@]JOFQDa@Ly@V[Ja@LiAZMDOFQDOFQFc@LODIBGBODQFOFQDc@LMFA?qA`@a@Lc@Lo@RA?QDeAXA@aATkB^MBSDSDOBc@HeAR]HC@c@Hc@Ha@Fu@NODc@HiB^mCr@G@WHqA`@eBf@ODQFWFIDeAXa@LWFKDKB{Ad@C@]HYFI@IBWDI@YDQBQ@UBM@Y@I?S@C?K?]?E?c@AIAYAKAIAo@GAAa@GC?_@GSEe@Km@Ma@IAAeAUw@QAAKCgB]AAOCwA[c@ICAuBc@wBe@mB_@QEOCc@KoAYsCm@_Ds@mAWWCk@I]Cw@Cq@?W@u@Bo@Fg@HE@SDc@HSFIBa@L[JE@aBh@mCz@OFyC~@E@]La@LE@EB}Ad@cCx@EBC?WJ_Bf@u@TUFIBA@UF?@IBiBj@UHUHcBh@sAb@_@Lc@La@Nm@RmInCA?sBr@UHaAZC@oExAuAb@uBn@UH}FhBw@Vo@Rw@Vm@P{Ad@}FjBcAZUFKDeA\\WHuDjAUFqAb@UFKDePdFc@NgA\\yDlAwBp@c@La@LsAb@SFa@Lq@R_Bf@[Ja@Lc@LE@[Ja@La@LG@[Ja@La@LEB[Ja@Lc@LGBkA\\wAb@a@LeA\\a@La@LODQFa@Lc@La@LODs@Tc@NMDu@Ta@Ly@VKBa@LcAZgBj@}Ad@IBa@LcAZYJyFdBa@LcAZcCj@o@Hi@F"
                     },
                     "start_location" : {
                        "lat" : 44.1398003,
                        "lng" : -79.1037992
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13.6 km",
                        "value" : 13553
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 633
                     },
                     "end_location" : {
                        "lat" : 44.245389,
                        "lng" : -78.9628551
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDurham Regional Rd 13\u003c/b\u003e (signs for \u003cb\u003eRegional Rd 13\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Rd\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "exylGhf}aNKo@AOG_@S_BM_AG_@COE_@COeA_ICOE_@COQoACOE_@COS_BKo@Ea@UeBIi@AEAGIo@Ga@?EAGGa@?EAGIg@AGIo@S_BGa@AEAG]oC_@oCIg@Gi@Ku@AGq@gFsBiOAK_@qCi@_ECM[aCKo@MaAE[YsBe@kDKo@QuA_@oCAIGe@AIG[m@sEIo@CMQqAc@aDAKYqBE]OaAIo@E]MaAKo@S_BKo@_@mCAOCOCOIo@Ko@AOg@oDCOi@_EG_@Io@CO[_CIo@Ko@AMGa@Io@Ko@Iq@CKEa@U_BAMQqAIo@Io@CMGa@AMGa@AMKo@Ea@Io@CO[_CIo@Io@U_BIo@Io@Io@Ko@Io@S_BIo@Ko@SaBIo@Io@_@oCIo@S_BKo@S_BIo@U_BIo@EYU}AKo@Ko@Io@Ko@Km@E[CSIo@Ko@S_BIo@Ko@Io@S_BKo@Io@Io@Io@U_BIo@w@_Gs@eFIo@i@_E_A_H]kCm@aEU_Bk@}DIc@m@wDAEsAiK_@eCcA}GgAuHMs@Ks@s@oFGg@Go@e@aEE]CQIo@U_BS_BU_BS_Bm@iEIc@m@kEGc@aBmLAKKo@Ks@Ik@Ks@U}AIk@Io@ACIk@Io@OkAO_AKm@UyA?AU}AIu@Gk@Go@AEGo@Go@Io@Kq@COQmAIo@G]OaAa@mCAKEUAMIo@Io@AKGc@SaBAKGc@UkBCQMaAu@}ECOAKk@wECMAKWoBQoAGa@YkBWiBOiAKo@[gCw@wFIm@?AiAoI]oCi@_EIm@?AIm@AAIo@]mCAAIo@CScBkMGc@AKACS{AS_BKo@QsAK{@EYEWCWEWIo@y@gGc@gDy@gGEWCWk@gEGQMeAEUEYcAuHEYCUEWOgAEWIo@EWS_BEWCWEWEWIo@_@oCEWIo@CSACEWCWEWEWIm@EYIo@gAuHYwBEWqAgJOeAEYCUCYMgAEWm@sFCUEYQ_BQgBg@yDs@qFCUYyBOeAMiAi@}DIq@Io@CMQqAIo@Io@CMQqAIq@}@_Ha@{CKo@E]AEMcAE[WkBQsAIo@UeBAGGe@]iCCQE]k@oEE[Iq@Iq@Io@Io@AAE]AQIo@?AOaB?AIo@Go@?A?AACOyAy@aHE]AQKw@AKe@mD?C?AIi@?CUaBCQCWAC?AQyA?EIk@?EGi@ACGk@E[CS[uCKw@?EIo@e@gEE]CQOmAASIo@E]CQIq@Go@E]CQQaBOkACSGo@CSE]UsBOmAAQIo@s@oGCSE]CQe@aEEe@Gg@Io@CQOmAOkAMeACKIo@Iq@Ea@CMIo@a@eDCYEWMiAEUCYc@eDk@{EIo@yAqLCUEYIo@S_B"
                     },
                     "start_location" : {
                        "lat" : 44.2101141,
                        "lng" : -79.125647
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 362
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 44.2485232,
                        "lng" : -78.9640929
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSimcoe St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eKawartha Lakes County Rd 2\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ut`mGzl}`NiCt@a@Lc@LgBf@aBd@EBqEpA"
                     },
                     "start_location" : {
                        "lat" : 44.245389,
                        "lng" : -78.9628551
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "21.8 km",
                        "value" : 21833
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 975
                     },
                     "end_location" : {
                        "lat" : 44.3246358,
                        "lng" : -78.7395085
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLittle Britain Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eKawartha Lakes County Rd 4\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ghamGpt}`NKo@Im@a@oCKo@U_BIo@Km@U_BKo@mB}MKo@Ko@[}BCOIo@_A_HKo@Io@u@oFIo@_@oCGg@Kw@AEIi@?ECOo@yEKo@?ECOEYIk@cAiHCOEWKo@yBmOIo@Ko@CQOmAU_BUeBgCiR_@oCu@oFS_BIg@AG_@mCk@_EuDgZWsBg@_E]wCIg@k@_Eu@oFa@oCMw@QuA_@oC_@oCOaAuB{NuAwJMu@aA_HIm@EUa@sC_@aCGa@EU{BsOCQ]aC}@wGW{ACWSqAiAyHKw@EYg@kDe@aDESc@qCOgAE]uAyJe@eDIq@G[}B_PEYiAgIE]QkAOaAG[S}ASyAE[y@}FKm@Ga@COOm@I[I_@GMQg@MUWe@KOKM[a@OOMM]Y]OYMk@Qm@OuAG[Bc@FWBKBWHIBc@LUHKDeAZUFMDeAZgBj@SDkBj@KDQDcFxAa@LMD{Ab@c@LKBUHiBh@IB{@ViBf@kCv@a@LkA\\]JODiANcA?aCa@eAm@u@y@]o@KOo@kAWcASu@aBcLKo@a@oCIm@U_BW_BOeAEYIo@a@mCIo@U_BKo@k@_EKo@_@mCyBmOIo@w@oFIo@w@mFU_BwA_KU}AIo@c@oCgBkLa@mCKo@Ko@Io@y@kFm@_Ea@oCYmBm@}Da@oCIo@oAmIi@mDW}Aq@mE}@qG}@aG_AiFwA}JAIKo@aCsPAIwA}JCOmAmIIk@SsAAOKk@?CyA}JQoACMW_BIo@G_@YoBKm@Ga@eAkHs@_FCKOy@i@sDKo@w@mFcA}Ga@mCW_BU_BYmBG_@Io@i@_Ek@_EIo@_@oCKo@Io@q@}Ee@aDaBmLm@eEQ_AMk@_@cAWg@c@s@]g@_@e@m@i@{Au@a@O]IA?s@Gu@Ci@@a@Ds@NsAb@a@LkDhAa@NcAZaNnEa@NoFfBc@NaB\\E@WDK@QB[?]@]?A?WAUC{@KyC_AQMqA}@IKg@g@kA_Bi@_A]{@O_@AEOa@U{@Ia@[}AIo@uBoOU}AIo@eD{USsA_@oC_@oCQeA{BgP}@kGg@sDk@}DIo@Ko@Io@Ko@Io@Ko@Io@{@kGWwBIeAEkAEoAUuIA{@Ci@Eq@Gw@MeAk@}DKo@}E{\\Io@a@oCa@oC_@mCKo@a@oCk@_EIm@{@cGW_BIo@Ko@Io@Ko@aBmLaA_HKo@Im@Ko@wBiOKu@Km@_@oCKo@Io@_B}KqAwI?EKo@_@oCKo@Io@m@_EE_@oAmIKo@Io@Ko@Ko@a@mCk@_EKo@yA{JKo@k@_EKo@U}AKo@Ko@a@oCIo@{A{JyA}JKo@w@oFaAuGs@{EcA_HIo@W}AAGiAgIIo@Ko@m@eEOiAIm@CQ?Ec@}CQqAIi@E]EW}@yG_BqLKu@AIAIGeAAs@?EAQDwAb@iF?IFm@@ODc@D[Bm@?O?EAKCMEMAGA?We@"
                     },
                     "start_location" : {
                        "lat" : 44.2485232,
                        "lng" : -78.9640929
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1752
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 130
                     },
                     "end_location" : {
                        "lat" : 44.339681,
                        "lng" : -78.74589209999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAngeline St S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_dpmG|xq_N[GG?W?C?I@E?[F[Hg@NcA\\C?mA`@WHwAf@kDjAMDQFoA^WLQFiE|AuIxCa@NiC|@eC|@mA`@}C`AgBh@yBr@iDdAc@PIDsAh@eCx@u@VqFfB}@XeA\\eA\\"
                     },
                     "start_location" : {
                        "lat" : 44.3246358,
                        "lng" : -78.7395085
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 438
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 88
                     },
                     "end_location" : {
                        "lat" : 44.3420667,
                        "lng" : -78.7433776
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAuk Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_bsmGx`s_N_@iCWsBEOEEA?KCSBSH_@Ja@NcAZo@R]LM?SAMEMKIQgA_H"
                     },
                     "start_location" : {
                        "lat" : 44.339681,
                        "lng" : -78.74589209999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 136
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 44.3414172,
                        "lng" : -78.7419474
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAlbert St S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}psmGbqr_NJKHIFKXaAr@}BPm@BM"
                     },
                     "start_location" : {
                        "lat" : 44.3420667,
                        "lng" : -78.7433776
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20 m",
                        "value" : 20
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 44.34126,
                        "lng" : -78.7420679
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{lsmGdhr_N^V"
                     },
                     "start_location" : {
                        "lat" : 44.3414172,
                        "lng" : -78.7419474
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "41 m",
                        "value" : 41
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 44.3410364,
                        "lng" : -78.7416585
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{ksmG|hr_Nj@qA"
                     },
                     "start_location" : {
                        "lat" : 44.34126,
                        "lng" : -78.7420679
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "qpvkGn_~gNvA|KrA~IjBtGzCpV|A`MnN{Bve@kHb_@wFp|@gM`TmCpViE`q@kKvfAoPteAqPbq@oK|k@wIncAqPhReDdDsArB_AlFuFd@eAfCeFzCiJvHmWzBsEfDyDbLyK`PoO~F}HjD_FfEgJ|EeObB_FXw@UUwC_DsB_CyDkEsEqFsJeMoCcH}@gEaGac@m]wfC}Hii@yOgkAgWcqBsSuwAaJio@mD{YmAuRu@s]_AqRi@oEgAkEmL_WiAsEs@wFc@_KsKqy@}V_mBew@_aGcL_{@}AqRw@_HaDuQwEq]eGid@uMyaAuOkkA}Gkg@eCsSeJmp@qFad@eEw\\}FuZ}DuTcCg[qDiXeR{vAkIgo@mJsn@aYiyBwR{yAeEqZwC{UcOojAkN}dAaTg{Aw]}gCoGsf@{Fs_@eEgWcDcWiCsUo@kKoAkNqCqUmCqSiIyp@_I{m@wJiv@cHgc@eEwY}BcRmHkm@qK{v@aGqb@iCsReAsGeC_NmEkWwC{RcBqPeBuPwCeTyC{RkHgb@uAoIUuDE_JLeQsDm`@uBkOkCmJgDcI{CyHuAgHaBcLiD}VsFaa@eCeSuA{KsFy_@{BqQuG_i@cVcgB{Hql@_CmNkBuNiAkJ_D{RuCqSeLey@kYetBiBeM_Ei[{AeNuEa[sI_l@}OefAcLiy@{l@aiE}VafBeMi~@cL}y@q^ofCel@qhE{Y_yB}_AmdHgToaBsImn@_ZwsB}l@_jEsEc\\_DaTuNxE}YtJ_TxGuWbIoPrDoLfCyIhCiFxAiC\\yBDqD[qPkDuN{CyK}BsDQwFp@gNlEcPfFokAp_@apBzm@sDt@i@FKo@Io@a@_DU_BsA_KeAaIw@}F}CoUqLm|@iMm_AyH_l@mLw{@{Ms`AmLu{@gJup@yCkUoLs{@_`@auCyHal@cHsj@{Kc{@{Qw_BaE_]qEu^g@_EwHxBgBh@qEpAKo@k@}Da@oCw@mFaD{TcEoZ_BoLeM{}@qRqxAoa@_tCoKiu@k@wBcAsBeAmAaCiAcCW_AJeAT}InCy^pK{C|@mCNaCa@eAm@sAiB{@{AyCmQ{C{SgG{b@aRqoA}Ug_Bc[uvBeHmg@mBuJyBiDiC_B_AYuCIkEfAsVdIwKdD{@LyA@m@EuEkAuC_CcD{Fq@eCqD{VoMy~@uCqSgByNc@mP_@yE_Hye@cG_b@sF}_@}NwcA{`@unCcBgMoDyWMmCv@eMCoC}@m@k@@eJrCow@zWsTrHeA\\_@iC]cCg@EyC`AoB^[QqAqHv@cBdAkDb@Hj@qA"
         },
         "summary" : "ON-10",
         "warnings" : [],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
