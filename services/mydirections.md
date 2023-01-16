# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
[https://maps.googleapis.com/maps/api/directions/json?origin=386+367,+Side+Rd+20,+Mono,+ON+L9W+6V4&waypoints=207219,+ON-9,+Mono,+ON+L9W+6J1&destination=Fleming+College+-+Frost+Campus?departure_time=1687906800?&mode=driving?avoid=tolls|highways&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE](https://maps.googleapis.com/maps/api/directions/json?&origin=Fleming+College+-+Frost+Campus&waypoints=207219,+ON-9,+Mono,+ON+L9W+6J1&destination=386+367,+Side+Rd+20,+Mono,+ON+L9W+6V4&departure_time=1687906800&mode=driving&avoid=tolls|highways&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE]
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "partial_match" : true,
         "place_id" : "ChIJq6p6ZumM1YkRwlenRs5y5SY",
         "types" : [ "establishment", "point_of_interest", "university" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "EiwyMDcyMTkgT04tOSwgT3JhbmdldmlsbGUsIE9OIEw5VyAyWjIsIENhbmFkYSIyEjAKFAoSCYcqBWZVACuIEUWvQF4MjVolEPPSDCoUChIJbbg9YvvgKogR2Yl7aNxWyis",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJbSJ0-OxVKogR6XXQpJg9sbk",
         "types" : [ "street_address" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 44.3420072,
               "lng" : -78.73946769999999
            },
            "southwest" : {
               "lat" : 43.9195752,
               "lng" : -80.1239585
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "126 km",
                  "value" : 125943
               },
               "duration" : {
                  "text" : "1 hour 47 mins",
                  "value" : 6444
               },
               "end_address" : "207219 ON-9, Orangeville, ON L9W 2Z2, Canada",
               "end_location" : {
                  "lat" : 43.928605,
                  "lng" : -80.05485569999999
               },
               "start_address" : "200 Albert St S, Lindsay, ON K9V 5E6, Canada",
               "start_location" : {
                  "lat" : 44.3410364,
                  "lng" : -78.7416585
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "41 m",
                        "value" : 41
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 44.34126,
                        "lng" : -78.7420679
                     },
                     "html_instructions" : "Head \u003cb\u003enorthwest\u003c/b\u003e toward \u003cb\u003eAlbert St S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ojsmGjfr_Nk@pA"
                     },
                     "start_location" : {
                        "lat" : 44.3410364,
                        "lng" : -78.7416585
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
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 44.3414172,
                        "lng" : -78.7419474
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eAlbert St S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{ksmG|hr_N_@W"
                     },
                     "start_location" : {
                        "lat" : 44.34126,
                        "lng" : -78.7420679
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
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 44.3420667,
                        "lng" : -78.7433776
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAlbert St S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{lsmGdhr_NCLQl@s@|BY`AGJIHKJ"
                     },
                     "start_location" : {
                        "lat" : 44.3414172,
                        "lng" : -78.7419474
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
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 44.339681,
                        "lng" : -78.74589209999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAuk Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}psmGbqr_NfA~GHPLJLDR@L?\\Mn@SbA[`@O^KRIRCJB@?DDDNVrB^hC"
                     },
                     "start_location" : {
                        "lat" : 44.3420667,
                        "lng" : -78.7433776
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
                        "value" : 134
                     },
                     "end_location" : {
                        "lat" : 44.3246358,
                        "lng" : -78.7395085
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAngeline St S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eKawartha Lakes County Rd 4\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Angeline St S\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_bsmGx`s_NdA]dA]|@YpFgBt@WdCy@rAi@HEb@QhDeAxBs@fBi@|CaAlAa@dC}@hC}@`@OtIyChE}APGVMnA_@PGLEjDkAvAg@VIlAa@B?bA]f@OZIZGD?HAB?V?F?ZF"
                     },
                     "start_location" : {
                        "lat" : 44.339681,
                        "lng" : -78.74589209999999
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
                        "value" : 980
                     },
                     "end_location" : {
                        "lat" : 44.2485232,
                        "lng" : -78.9640929
                     },
                     "html_instructions" : "\u003cb\u003eAngeline St S\u003c/b\u003e turns \u003cb\u003eright\u003c/b\u003e and becomes \u003cb\u003eLittle Britain Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eKawartha Lakes County Rd 4\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_dpmG|xq_NVd@@?@FDLBL@J?D?NCl@EZEb@ANGl@?Hc@hFEvA@P?D@r@FdA@H@HJt@~ApL|@xGDVD\\Hh@PpAb@|C?DBPHl@NhAl@dEJn@Hn@hAfI@FV|AHn@bA~Gr@zE`AtGv@nFJn@xA|JzAzJHn@`@nCJn@Jn@T|AJn@j@~DJn@xAzJJn@j@~D`@lCJn@Jn@Hn@Jn@nAlID^l@~DHn@Jn@^nCJn@?DpAvI~A|KHn@Jn@^nCJl@Jt@vBhOJn@Hl@Jn@`A~G`BlLJn@Hn@Jn@Hn@V~Az@bGHl@j@~D`@nCJn@^lC`@nC`@nCHn@|Ez\\Jn@j@|DLdAFv@Dp@Bh@@z@TtIDnADjAHdAVvBz@jGHn@Jn@Hn@Jn@Hn@Jn@Hn@j@|Df@rD|@jGzBfPPdA^nC^nCRrAdDzUHn@T|AtBnOHn@Z|AH`@Tz@N`@@DN^\\z@h@~@jA~Af@f@HJpA|@PLxC~@z@JTBV@@?\\?\\AZ?PCJAVEDA`B]b@OnFgB`@O`NoEbA[`@OjDiA`@MrAc@r@O`@Eh@At@Br@F@?\\H`@NzAt@l@h@^d@\\f@b@r@Vf@^bALj@P~@l@dE`BlLd@`Dp@|EHn@Jn@^nCHn@j@~Dh@~DHn@F^XlBT~AV~A`@lCbA|Gv@lFJn@h@rDNx@BJr@~EdAjHF`@Jl@XnBF^Hn@V~ABLPnAxA|J?BJj@@NRrAHj@lAlIBNvA|J@H`CrPJn@@HvA|J~@hF|@`G|@pGp@lEV|Ah@lDnAlIHn@`@nCl@|DXlB`@nCl@~Dx@jFHn@Jn@Jn@`@lCfBjLb@nCHn@T|AvA~JT~Av@lFHn@v@nFHn@xBlO^lCJn@j@~DJn@T~AHn@`@lCHn@DXNdAV~AT~AHl@`@nCJn@`BbLRt@VbAn@jAJN\\n@t@x@dAl@`C`@bA?hAONE\\KjA]`@MjCw@hBg@z@WHChBi@TIJCb@MzAc@LE`@MbFyAPEJEjBk@REfBk@dA[LETGdA[JETIb@MHCVIJCVCb@GZCtAFl@Nj@PXL\\N\\XLLNNZ`@JLJNVd@LTPf@FLH^HZNl@BNF`@Jl@x@|FDZRxAR|AFZN`APjAD\\hAfIDX|B~OFZHp@d@dDtAxJD\\NfAb@pCDRd@`Df@jDDXJv@hAxHRpABVVzA|@vG\\`CBPzBrODTF`@^`C`@rCDTHl@`A~GLt@tAvJtBzNN`A^nC^nCPtALv@`@nCt@nFj@~DHf@\\vCf@~DVrBtDfZj@~D^lC@FHf@R~At@nF^nCfChRTdBT~ANlABPJn@Hn@xBlOJn@DVBNbAhHHj@DXBN?DJn@n@xEBN?DHh@@DJv@Ff@^nCHn@t@nFHn@Jn@~@~GHn@BNZ|BJn@Jn@lB|MJn@T~AJl@Hn@T~AJn@`@nCHl@Jn@"
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
                        "value" : 362
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 44.245389,
                        "lng" : -78.9628551
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSimcoe St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eKawartha Lakes County Rd 2\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ghamGpt}`NpEqADC`Be@fBg@b@M`@MhCu@"
                     },
                     "start_location" : {
                        "lat" : 44.2485232,
                        "lng" : -78.9640929
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13.6 km",
                        "value" : 13553
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 627
                     },
                     "end_location" : {
                        "lat" : 44.2101141,
                        "lng" : -79.125647
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDurham Regional Rd 13\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ut`mGzl}`NR~AHn@DXBTxApLHn@j@zEb@dDBXDTLhADVBX`@dDHn@BLD`@Hp@Hn@BJLdANjANlABPHn@Ff@Dd@d@`EBPD\\BRr@nGHn@@PNlATrBD\\BRFn@BRNjAP`BBPD\\Fn@Hp@BPD\\Hn@@RNlABPD\\d@fEHn@?DJv@ZtCBRDZFj@@BFh@?DHj@?DPxA?@@BBVBPT`B?BHh@?@?Bd@lD@JJv@@PD\\x@`HNxA@B?@?@Fn@Hn@?@N`B?@Hn@@PD\\@@Hn@Hn@Hp@Hp@DZj@nED\\BP\\hCFd@@FTdBHn@PrAVjBDZLbA@DD\\Jn@`@zC|@~GHp@PpABLHn@Hn@PpABLHn@Hp@h@|DLhANdAXxBBTr@pFf@xDPfBP~ADXBTl@rFDVLfABXBTDXNdApAfJDVXvBfAtHHn@DXHl@DVDVBVDV@BBRHn@DV^nCHn@DVDVBVDVR~ADVHn@DVNfADVBTDXbAtHDXDTLdAFPj@fEBVDVx@fGb@fDx@fGHn@DVBVDVDXJz@PrAJn@R~ARzA@B@JFb@bBjMBRHn@@@\\lCHn@@@Hl@?@Hl@h@~D\\nChAnI?@Hl@v@vFZfCJn@NhAVhBXjBF`@PnAVnB@JBLj@vE@JBNt@|EL`ABPTjBFb@@JR`BFb@@JHn@Hn@@LDT@J`@lCN`AF\\Hn@PlABNJp@Hn@Fn@Fn@@DFn@Fj@Ht@T|A?@TxAJl@N~@NjAHn@Hj@@BHn@Hj@T|AJr@Hj@Jr@Jn@@J`BlLFb@l@jEHb@l@hER~AT~AR~AT~AHn@BPD\\d@`EFn@Ff@r@nFJr@Lr@fAtHbA|G^dCrAhK@Dl@vDHb@j@|DT~Al@`E\\jC~@~Gh@~DHn@r@dFv@~FHn@T~AHn@Hn@Hn@Jn@R~AHn@Jn@Hn@R~AJn@Hn@BRDZJl@Jn@Hn@Jn@Jn@T|ADXHn@T~AHn@R~AJn@R~AHn@^nCHn@Hn@R`BJn@Hn@R~AHn@Jn@Hn@Hn@Hn@T~AHn@Hn@Z~BBNHn@D`@Jn@@LF`@@LF`@BLHn@Hn@PpA@LT~AD`@BJHp@Jn@Hn@F`@@LJn@Hn@Z~BBNHn@F^h@~DBNf@nD@NJn@Hn@BNBN@N^lCJn@R~AJn@L`AD\\Hn@N`AD\\XpB@Jb@`DPpABLHn@l@rEFZ@HFd@@H^nCPtAJn@d@jDXrBDZL`AJn@Z`CBLh@~D^pC@JrBhOp@fF@FJt@Fh@Hf@^nC\\nC@F@DF`@R~AHn@@FHf@@F?DF`@@F?DF`@Hn@@F@DHh@TdBD`@Jn@R~ABND^BNPnABND^BNdA~HBND^BNF^L~@R~AF^@NJn@"
                     },
                     "start_location" : {
                        "lat" : 44.245389,
                        "lng" : -78.9628551
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
                        "value" : 348
                     },
                     "end_location" : {
                        "lat" : 44.1398003,
                        "lng" : -79.1037992
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLake Ridge Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 23\u003c/b\u003e (signs for \u003cb\u003eRegional Rd 23\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "exylGhf}aNh@Gn@IbCk@bA[`@MxFeBXKbA[`@MHC|Ae@fBk@bA[`@MJCx@W`@Mt@ULEb@Or@UNE`@Mb@M`@MPGNE`@M`@MdA]`@MvAc@jA]FCb@M`@MZKDC`@M`@MZKFA`@M`@MZKDAb@M`@MZK~Ag@p@S`@MRGrAc@`@Mb@MvBq@xDmAfA]b@OdPeFJETGpAc@TGtDkAVIdA]JETGbA[|FkBzAe@l@Qv@Wn@Sv@W|FiBTItBo@tAc@nEyABA`A[TIrBs@@?lIoCl@S`@Ob@M^MrAc@bBi@TITIhBk@HC?ATG@AHCTGt@U~Ag@VKB?DCbCy@|Ae@DCDA`@M\\MDAxC_ANGlC{@`Bi@DAZK`@MHCRGb@IREDAf@In@Gt@CVAp@?v@B\\Bj@HVBlAV~Cr@rCl@nAXb@JNBPDlB^vBd@tBb@B@b@HvAZNB@@fB\\JB@@v@PdAT@@`@Hl@Ld@JRD^FB?`@F@@n@FH@J@X@H@b@@D?\\?J?B?RAH?XALATCPAPCXEHAVEHCHAXG\\IBAzAe@JCJEVG`@MdAYHEVGPGNEdBg@pAa@VIFAlCs@hB_@b@INEt@O`@Gb@Ib@IBA\\IdASb@INCRERELCjB_@`AU@AdAYPE@?n@Sb@M`@MpAa@@?LGb@MPENGPGNEFCHCNEb@MPGNGPENGLEhA[`@MZKx@W`@MPENG\\KDAr@UNE`@MRI^K~@[pBm@nA_@PGXIHCbBi@@A@?bA]r@UNG`@Mb@O`@MdBm@dEuAlBm@@AdCy@@?RIl@S~@[d@O^M@?h@Q`A]\\Mv@WpAa@n@Sp@U~Ai@hA_@"
                     },
                     "start_location" : {
                        "lat" : 44.2101141,
                        "lng" : -79.125647
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "41.0 km",
                        "value" : 41007
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2444
                     },
                     "end_location" : {
                        "lat" : 44.0297805,
                        "lng" : -79.59313969999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDavis Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "w`llGv}xaN`@lCVhBV|AFd@DXDTf@fDPlADXPlAPpAHh@?BL|@@DNbAD\\VfBNhAXjBJv@RxAT|A@FPrA?BLv@Fd@BLFh@Hf@?FLx@Z|B@FFf@DXXrBJn@?DDRBNHt@Hd@D\\DZHh@XjBVlBDXFd@Lz@R|ABNVlBTbBLz@RtADZPlAHh@?Bf@lDL`AFb@Lz@VlBPnAD\\`@rCRxABPHp@Hf@TbB?@Hn@Jn@?DRtA?BJn@Hj@?BJl@BVDXHl@NfAHf@F^BND^BLHp@\\`C^jCL|@@@Hl@T`BHl@@@h@zD?@PhABRDZDRd@jDBP^dC@H@HRtA@FFf@BNJn@Z|BBNF^BND^BNF^Hn@Jn@BRHn@T|AFZFh@Jt@Hf@T~AJn@?D^hCJn@?DJn@T|AFh@@DJn@Hn@RvALv@Ff@@DJn@LbAXnBLz@j@|DRvA@F^lCBNF^@HFd@DXNdA@JHb@?Bh@xD@B`@rCRvAt@lF@F`CrPVbB`@rC?BHf@Jp@@BBTNdA@B^jC@BHh@Hn@@BHj@Jr@Hj@?B`@hC@HF`@?B@B@JF^?BRlA@J@BHn@BNDZBHFd@?BLt@Fd@?B^hCJr@@FFb@Jr@@FFb@Hn@@BPnA@HJn@?BPlAL|@@BPjAXtBRvABRF^Hr@Hf@Hn@Hn@T~AR~AT~AVpB@FJv@D^h@bEFf@h@dEHn@Jn@BZNbA\\nC?DRxAJt@Fh@Hn@Hl@\\pCBVDXHn@DTl@xEr@nFrA|JdAzHBRJn@n@zEBPPlABPn@|EBPPlAL`ADZBRPjABRh@|DPjALbAPlABPNhADTHn@DZf@nDF`@?Bt@jFBN|@xGd@hD@H@Fp@~E`@tCf@vD@Fz@tGHn@@H^nCFd@@HRtAr@nFR~AHn@BNTbBJn@BTDVDVbApHDZt@nFHn@BLF`@@L`@pCD\\BPf@lDBTNhANfAT`BJn@BTHn@T~ADVXvBBTDXHn@^nCDTBXd@dDBVNfAhAnId@fDb@dDNhA^lCVrBFZ\\nCBPJn@Fj@Jr@h@~DJn@Hn@Hn@Hn@Jn@Hn@Hn@Hn@Jn@DZBRHn@T|AHn@^nCT~AHn@Jn@Z~BV`BLz@Hn@Hj@@BHn@RhBBPBRBTDXBND\\BP@FDVHn@PtARvAHp@BNFh@Lt@Jl@@LF`@TbBDX`@~CHh@@FBRBT^rC?@Hn@|@tG@H\\fCF`@DRHn@?@Hl@Hn@?@Hl@Jn@Fj@@BTdBR~ARxALbAN`AJv@Hn@Hp@DZDRRxAh@dE?@^hCb@bDPlAHn@Hf@@F@LF`@@DFh@Hf@@FHl@Hn@PhA@LbAtHj@dEJp@R`B^pCJn@T`Bd@nDVrBf@rDl@lEVhBBT@BBXRpA@Nb@|CF^\\bCT~ADZPrAPlAPjAHn@`@lCDXVtB^nCHn@L`AN~@XnBFh@@BFj@^nCj@|DrA~Jj@|DHn@T~AHn@?@h@|D@@Hl@Hp@h@zDT~AHn@T~AHn@Jl@ZdCN`AZxBxBzOBJf@rDLz@F`@Hn@Jn@~@|GBJr@bFv@lFt@lF^fCb@tC^pCvA|J`A|G^nCXpBPjAt@jFxAbK`@nCnAjIHn@b@vCt@bFTvAJt@TxAHl@Lv@Ff@DVDVj@|D@D^fCPhABTHj@@BJt@DVN|@?@@FJn@VhBRpAJp@Jv@PfA?DRzA|@zGRbBJn@ThBTbBRxANhABTF^?@L|@F`@Hn@@LL~@F^R~A@D@Hn@bF@@Fh@DXDZPtA@B?DHh@@DHh@Jt@NdABPD\\^lCXrBDTNfANfA@LRpARbB^hCr@bFDTBR\\hCF`@Fb@N`AHf@^jCJr@RrAJx@@BPhAL~@pB|MJl@RxA@DHl@Jj@Fd@BL^lCRpAHf@Ff@F`@TxAf@lDn@pEt@jFXjBp@hFNbAL`Ab@zC@Ft@dF`@lCT|AfA|HnAfJVhBr@bFb@~C^lC`@nCBLjDjVBPtBxNp@`FJp@ZrBf@lDBNBRnAzIfA`IDRx@~Fh@vDfAdIJp@XpBhAdIFd@zA`LhAlI\\nC`@pC?FJp@lAfJ\\hCn@xEVfBZxBFf@Jr@BPd@vCRpAv@bG`@lCJn@NfADVLz@h@hDdCzPBNpA|I`@nCDZF^`@pCR|Av@lFLv@@^NdAv@xFj@vDHf@\\~Bz@`GpAzIj@hE`@dCBL`@hC\\vB^~BRvAZhB@LBNPpA`@~C`@vCDZRjBBTRnBj@vEBZN^hAjInBdOAP?FVnB^nCVvBrAvJz@tG^lC?@Hn@XpBRbBP`BPzAl@|Db@pC^pCRpA?DNhAT`B\\bCR|AH`@ZtBZ~Bf@pDVjBZ|Bf@jDHb@^jC?@@L`@dCLx@DVlApI^lCh@zDD^VlBr@~E|@nGZ|BT|A^hCl@hEj@zD^nC`@xC^lCHd@PlA?BTfB\\nCDZVbBVjBZ|BBL@HBVR~A\\bCXnBHl@T~A\\pBDZPtARvAFp@Fl@Hl@?@T~AJbAHr@Hj@DRNdAJj@f@fCJn@DTN`AN~@Fj@VrBHx@L`ADd@Fl@@DBV@LHj@DVFl@Lp@LlA?B|AdKf@fD\\nCb@dDV|Aj@xDZ|BBNp@fF@F^jCf@|DFd@`@pCR~AHl@NvA~@vGt@dFt@vFJx@VzBh@nDHp@PlAHf@BJ@HFd@Jn@Jx@r@tERrAX~B\\jC@NF\\lAbKv@|Fh@|DJt@R|ANbAVlBZ|BBT`@xCVxBBLBLDJJLd@pD|@xGF`An@xELfAb@`DNpAh@~D@J`@vCLr@Nr@fAjH|@~Gp@`F~@vG`@lC\\dCBVR~AFj@`@nCL|@R~ATbBDTFb@dA|HR~AHb@j@|DRpABN\\bCT~AJn@@Hp@lCJXPj@@Dd@lAPd@LVHPj@nATd@^~@HPRf@t@fBHRN\\BHdAhDXfAFTb@dBN~@z@`F\\tDJr@j@lFz@vIFn@`@bEFl@TtC@J@b@DdA?|A?h@?JChAEbCGxBAb@A~A?l@?F?p@?DBhA@j@@ZFfA?DDj@Fz@Hh@Hp@VzAh@vC\\jBFZZfBl@fDnAbHhAdH`@dC@HT|Ab@tCHh@\\pBD^@?l@`EdA|G@HjAdJBV?@f@nENrAl@nGFh@VjCZvCf@bFN|@`@rC\\jBfA|Hh@xCJp@b@jCZfBX|APdAN~@ZfBFv@L|@XdBv@zEJn@V|AV|AJn@`@fCb@lCJ`AHb@t@hFRl@h@xDLv@NjALz@Jp@BNFh@F^^lCT~AHn@Hn@T~AHn@T|AJn@Hn@h@~Db@dCBTHd@@LXlBPpA\\~BL|@p@~EXlB`@fD@Fr@pFl@lEF\\n@tEF^@Ff@tDDVVrBDZZlCRbB@NNlA^hDRhBNzAXpCBVN~A\\bDC\\@XD^BVX~BD`@L~@Fn@Fl@DXD\\"
                     },
                     "start_location" : {
                        "lat" : 44.1398003,
                        "lng" : -79.1037992
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "31.7 km",
                        "value" : 31706
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1442
                     },
                     "end_location" : {
                        "lat" : 43.94643809999999,
                        "lng" : -79.97141769999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-9 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cqvkGbpxdNNrAj@fEL~@\\zBz@lF^nBRzABLBFDHVd@f@jCJf@@FLt@`@tBb@hCN~@V|APdANbAPlAJ|@DVFf@PlAd@bD^tCZ`Cb@rDPfBVnBl@xEn@vEFb@^lCBTPzAJz@Hn@DXV`BNnA@Ld@tDl@tEVtBHf@?@Lx@X`Cb@`DTjB`@~CHdAx@pHLfA`@tCFf@b@`DlCrSZdCRzANjAL~@p@|EBPLbAPtAD^b@vDPxAL|@j@vEJv@?@BRPzAJr@XrCJjABPF|@JtADp@?Bb@pHJtA@NN~A^nDvArLPzAv@tGbA~HTpAJp@ZlBhCzORjAbA|Gp@tEx@rFB^@Ph@nEHn@PpAHl@b@fD^jCrArJFb@Nb@tA|JBHd@lD^jCNlAd@hD@Jp@bFL|@XnBh@|D`AlHbA|GTvA`AxGJn@VnBNdAT|AHn@ZzBn@|Ej@fEr@fFD\\l@tE`@xCXpBHr@VbBJz@fAzHLx@d@pDbAzHjA~H\\`Ch@tDXjBzB|OTzA@Fz@dGt@~ET`B`@tCb@~Cd@nD@D\\hC@FZbCvA~Jb@~CHn@t@lFJx@N~@XxBpAtJHn@LhA^nCPlA`@fDd@lDFb@pA|JHn@t@|FdA`IX|BT`BVtB^pCb@jD`@zCn@fFJ|@@BPtAJx@Hf@PjAb@fE`@dDJh@BPXbCb@dDR`APfAb@fD^xC`@pCHr@Jx@T~A^nCXvBj@tEBJ@N@H\\dCf@`E^lCHp@Jn@b@bDDZL~@PjA`@|CF`@VnBPzAFb@|@xG@D@J@JXtBv@xFf@zDR~AHn@Hl@T~Al@xEv@`GR|AL~@bAzHPnAz@`Hr@nFZfCRxAv@jGXtBD`@BLdAlIVhBPtAJx@Hp@n@bFLhA\\nCPnAThB?@Hj@^rCFb@@FT`BRvAn@dEDXJr@ZlBJr@?Bb@bCLr@d@rCHj@`@dCR~ALz@r@dFHn@DVHj@NhAHn@XtBDXf@~DVjB@Hv@hGR~AT|A`@rCd@tDJ`AJt@XzBLx@Hn@PvAxAzKBR`@|Cf@~DHl@dBdN`@`Dl@~Dl@nEt@vFhAzHPnAJv@ZbCz@bGT`BRpAFp@Hr@H`APnCDb@@JPjCh@lGV`DJhAHz@BJJ|@TpATnAd@`Cd@~Bj@jCn@rCf@jCb@zBf@jCn@|C\\zBHd@@LN`AD`@PpAHh@\\tCDZ\\nCBRFd@Hv@X|B@D@JTlBDb@@@Db@TjBZpCDXFb@Fh@Hn@Df@TfBFf@D\\`@`D@NL~@Hv@r@fF@@@L`@lCHp@T|Af@jDb@~C?B^lCHl@^lCHl@XpB^jC^vCd@`DJx@R|AV|BDXh@fERjBBLD`@f@~DXbCn@`F\\hCbAbHHh@VbBf@hDZzBd@bDhArIp@fFd@lDDX\\bC@H\\nCn@vEd@nDZbC^nCd@tDf@vDL~@xA~KBNHn@Hn@r@nF`@|C^hCh@`E`@|CVfB`@dDv@jFFb@L~@Ff@PjA^lCNfARvAVdBfA|Id@bD`@|CXtBBTRzAb@fDfA|I`@pCV`B?DX~AJj@j@|Cj@fD|@bFZnBPdBBXDn@BXTjDT~CFr@BNRxB@FJdAVrB^nC?DDTBR@Hh@jE^lCtA`KvAbKZ`Ch@~DFb@@JFb@NjAVrBfAjIr@nFp@hFJt@fAjIt@xFFj@`@tCPvAr@hFTfBHn@Hn@XxBPpAD`@VlBDXZxBb@fDf@vDHr@Jl@PtAThBNdAv@|Fn@tEbAxHDRbAvH?@r@jF@HNbAb@`Dp@xF?Dn@hFx@tFdApHv@`GR|APpABNZ~B@LF`@d@hDVrBDZDRDZDZn@`FNdAHh@^rC^rCDZf@lD@Pz@lGpApJ@J@DHj@\\nCPxAr@fFRnAv@hG`@~CBLPpAPvA\\nCPrAHj@XxBR|APjAZ|BBVT`BBTDVRzA?Bf@tDThBbArHBN`AtHLv@PlAR|AR~ARnAJr@Jv@DZ^vC\\zBDb@h@lEFb@b@hDpAnJn@tEJrADt@?P@FJdDFhA?FBTB`@Fv@Jz@L|@PdA@DRbAZlAVz@Xx@Vn@\\t@`DrG`BfDl@lA\\z@LXZ`ADTRx@Px@RpAJdAFp@@D?DBR@T@JFvEPlEDpB@\\FzBFnBDzA"
                     },
                     "start_location" : {
                        "lat" : 44.0297805,
                        "lng" : -79.59313969999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "7.0 km",
                        "value" : 6977
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 293
                     },
                     "end_location" : {
                        "lat" : 43.928605,
                        "lng" : -80.05485569999999
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eON-9 W\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "ghfkGjlbgNL~C@r@DjA?@@BF`@F|BLdE@\\@RH|BHdADx@NxBFr@VvC`AhI`@jDBTBPV|BL~@?@Z|BL~@DXHh@d@hDDTNhAj@zDT~AHl@\\dCT~Al@dEh@xDJn@VbBJv@RtAV~A@FFd@@HHd@Jv@TtAHl@`@lCJp@T~Ar@xENbAJl@Hl@Jn@?@f@bDNfAPdANfAPdANfAf@bDf@fDDZXzB|AfLl@lEBR?BPxAbApH^lCZ|BHt@Hn@T|AVlBb@nD@BPzAf@~DJr@Fj@TfBPvAF`@@L@B`@bDBVJr@Hn@Hl@PrATlB`@|Ch@dEh@dENlAdAnIpA|J^nC?D\\hCJbAVxBl@`FZrBn@jEVdBPnAnA`JrA|JXpBz@dGHp@NfALv@ZzBDZRxAdAbH@J|@~FL~@XlBF^BNVhBDRL~@Hn@Hb@Fh@~@jG\\bC^dC\\dCb@zCb@bDh@tD^hCh@|Dr@hFhAlIVbBBPDX`@tCBVp@zENdA"
                     },
                     "start_location" : {
                        "lat" : 43.94643809999999,
                        "lng" : -79.97141769999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "16.1 km",
                  "value" : 16095
               },
               "duration" : {
                  "text" : "13 mins",
                  "value" : 805
               },
               "end_address" : "386367 Side Rd 20, Mono, ON L9W 6V4, Canada",
               "end_location" : {
                  "lat" : 44.0296892,
                  "lng" : -80.1127152
               },
               "start_address" : "207219 ON-9, Orangeville, ON L9W 2Z2, Canada",
               "start_location" : {
                  "lat" : 43.928605,
                  "lng" : -80.05485569999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 936
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 43.9261444,
                        "lng" : -80.0660328
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eON-9 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wxbkGzurgN~@hHT~AHn@f@tDFb@T|ALdAJn@hArIT|ABTj@dETdBh@bEh@zDp@|E"
                     },
                     "start_location" : {
                        "lat" : 43.928605,
                        "lng" : -80.05485569999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1102
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 43.9200568,
                        "lng" : -80.0763738
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eON-9 W\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "kibkGt{tgN\\dCJn@BVPtA@HBPBLFf@RpA?@Lv@F^?@FXFZ@BDZFZBLRx@DLBLJ`@HVTn@Xt@Zp@^r@HNR`@T\\LPh@t@rAbBxBlC^b@b@f@bAlAlBzB@@^d@xBdCTXLLZ\\tAzA\\b@"
                     },
                     "start_location" : {
                        "lat" : 43.9261444,
                        "lng" : -80.0660328
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "7.0 km",
                        "value" : 7012
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 384
                     },
                     "end_location" : {
                        "lat" : 43.9730239,
                        "lng" : -80.11090759999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eON-10\u003c/b\u003e (signs for \u003cb\u003eOrangeville\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOntario 10 N\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kcakGh|vgNRl@PXLTRXHVBBDTBP?L?RAXERI^Mb@Gh@Wx@O`@eAbDoA~DIRqAjDyAzCi@hAc@x@mCtE?BIf@MPkBnC_AlAeAlAc@f@]^e@d@s@n@iEzDMLoCjC]ZqCnC_@\\{DtDu@t@mAlAi@p@g@n@GHs@nAc@~@Sb@O^q@rB_@lAoB~GuBjHa@vAw@`Ci@bBWj@a@z@k@lA[j@]n@[j@I?E?A?A?iAxAWX{@z@{@r@cAt@m@^KTc@RmAh@_@LSF{@Ri@LcB\\q@JqARkCb@e@FiBXaC^gDh@yDl@uAVYDc@H{Dn@_@H[DsATw@LiBZaC`@mCb@e@Hi@Hk@HI@m@Ji@JcBZ{AZWDa@F_@FSDo@Jq@Hu@LcANKBe@FaANkAP{@L_ANu@LkAPu@Jm@J{@Jm@Jq@Jm@HG@s@Jm@Jc@Fk@Jg@Fa@F[FYDYD]F_@DWD_@Fe@Fg@Hq@J{@NYDcAN{@Na@FWD[D]Fi@HA?c@H[DQDSB[FI@a@FMBc@He@Fa@H]Dm@J]F_@Fa@F]Fi@H[DYF_@F]DMBC@a@F_@FYDWFUBI@YFe@F[FaANi@Jm@HUDE?MBQBA@I@MBSBKBM@KBK@IBUBQDK@QBSDQBQBWDYFg@Fm@Jg@He@Hc@FeAPkARK@_@F_ANm@JI@eAPcAP{@Lg@HE@m@Hg@JaAN{ATcAP[DaBV_Df@kCb@"
                     },
                     "start_location" : {
                        "lat" : 43.9200568,
                        "lng" : -80.0763738
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.1 km",
                        "value" : 6096
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 238
                     },
                     "end_location" : {
                        "lat" : 44.0270361,
                        "lng" : -80.1239585
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eON-10\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "knkkGdt}gNcJtAuF|@kBXa@Fu@Ls@JkBXaBXG?a@HyFx@?@iBVwF|@{ATq@JgJtA_ANsJxAoKbBmAPyFx@I@eBVwF~@_ANc@FmFz@wCb@a@F_BXmCb@I@kAR]Fc@HiBZeAPoDp@c@FiCf@UBiBZcBXiBVs@JMByARmBVs@HyAP_D\\uANA@qC`@wCb@}APw@J{Cb@wCb@mFv@c@FmAP{IpAc@Ha@FuBZmFv@yGbAc@FgAPa@FgAPy@LyCb@_IlAsEp@mC`@cSzCqFz@}HnAqDj@"
                     },
                     "start_location" : {
                        "lat" : 43.9730239,
                        "lng" : -80.11090759999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 949
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 44.0296892,
                        "lng" : -80.1127152
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSide Rd 20\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_`vkGve`hNUqBgAoIoA_KkAqJW{AsAyD]yAK}@M_A[gCIo@Io@Io@Io@Io@Ko@Io@OmA"
                     },
                     "start_location" : {
                        "lat" : 44.0270361,
                        "lng" : -80.1239585
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "ojsmGjfr_Nk@pA_@WUz@_BtEz@jHV\\lAEtDkAt@IbArGzL}DhUwHna@oNpN{EzDaA^?r@l@Lb@WlEg@|IJhCrE|\\dNr`A~OpfAz]ddCdKhs@fAlJ`@jObBtOj@~D~Hzj@xK|w@jA|ExA`DrBfCzAhAjDlApANtA?pAKd^cLtIkCtDB|CnAnCjDvAvEfFr^fDnVzGjd@bJ|m@vIhm@hK~q@|P|iA`P`iAjFl]pBnEzBfBdE`@bE_ArIeCdIaClWyHlDGpC~@tCrDtA~FvCxSdQtmApOdfA|Hjj@tKhz@bNdbAxSnzAT|AvEuAnGiBhCu@R~ANhArCrUpBfPnA|JfEj_@`D|XpGzi@tIdr@tHbl@fHlk@hLbz@va@f}C`Mb~@tGjg@|RzuApMt`AvIpp@l`@jvCfH~h@L~@xAQbN{DtLuDfPcFv{@gXzpAua@vf@sOrCW~CDhQpDvWtF~Ex@lCHnGw@fWeHrQoDhXgIbo@qShGsBrGuBhA_@`@lCn@fEz@|Fz@fGvAdKzD`YfDhV`Lpy@`Kts@z\\`aCnP`kAhT~aB`RptAvb@`aDjw@~}FxV~hB|`@dqCbZdxBr_AdxGfOdhAhO~dAbPbhApCdSvAhMlEl[|Fld@lDtWzJfs@tWvkBtFhb@nBrLdBpNbJzo@pMbaAzIrp@pInn@lEl\\jIdl@~I|o@jA`FjAdDlE`KbBdFtAbGpCxTlBxR^jGC|EQnNf@pJjG`^|Knu@xEbd@vGza@~Hxg@tDfVrBfOxIpn@rIzp@`AnJj@zHlApK|En\\d@dAbApFlDrTvDdZdJls@bWdrBbAvLp@zKxC~W|CxU|Fr^`EzZnHdh@zE~]rPhmAlb@j{Cp[hdC|n@v}EnGbc@|Hzj@vLb_A`Kru@`CzPl@vHtB|VfGl[zDxTrBnPvDt[pHhj@pJju@rP`nAp\\ffCvFh`@vC`Rb@nGzBnTbGxc@rNpgArIbp@xZx}BrU~fBdKlv@fDjW`ApJp@jLt@lEdBrFnI~PlAlDrA|It@bYpBde@hDtZ`DfUhHjg@tHng@jMt_AzFpd@zNhjAvPllAbZzvBbLlz@rBxLjC`HxIlLtKfMpBxBp@pA|@`BLx@Q`B}@hDqFbPuHtNcClEgEbFqH~GiU`UgChEuBdG_IdXoCxG_BfCG?cBrBiFdEo@h@mBv@}EfAc[|EwOjCu\\xFiZnEsa@jGat@fLoyAhUynAnRce@|Hat@tJovA~SoPjCqDj@UqBwCoUcBmMqBsGY}By@wGy@mG"
         },
         "summary" : "Davis Dr and ON-9 W",
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
