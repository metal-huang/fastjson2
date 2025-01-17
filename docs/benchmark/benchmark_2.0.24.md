## EishayParseBinary
| aliyun ecs spec | jdk version 	|	fastjson2UTF8Bytes	|	hessian	|	javaSerialize	|	jsonb |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1138.18	|	286.071 (25.13%)	|	46.459 (4.08%)	|	1716.752 (150.83%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1177.362	|	255.15 (21.67%)	|	49.214 (4.18%)	|	2732.249 (232.07%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1216.61	|	260.948 (21.45%)	|	54.562 (4.48%)	|	3089.633 (253.95%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	830.354	|	204.364 (24.61%)	|	43.034 (5.18%)	|	1417.351 (170.69%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1076.757	|	194.435 (18.06%)	|	40.789 (3.79%)	|	2125.171 (197.37%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1105.943	|	219.128 (19.81%)	|	39.049 (3.53%)	|	2249.276 (203.38%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1407.15	|	381.353 (27.1%)	|	58.313 (4.14%)	|	2880.638 (204.71%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1681.493	|	377.671 (22.46%)	|	61.819 (3.68%)	|	3005.056 (178.71%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1590.572	|	332.086 (20.88%)	|	67.152 (4.22%)	|	3309.683 (208.08%) |

## EishayParseBinaryArrayMapping
| aliyun ecs spec | jdk version 	|	fastjson1UTF8Bytes	|	fastjson2UTF8Bytes	|	jsonb	|	kryo	|	protobuf |
|-----|-----|----------|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1462.54	|	1647.232 (112.63%)	|	2730.417 (186.69%)	|	1665.471 (113.88%)	|	1006.406 (68.81%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1503.555	|	1775.372 (118.08%)	|	3908.082 (259.92%)	|	1618.088 (107.62%)	|	1381.03 (91.85%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1672.701	|	1981.623 (118.47%)	|	5092.478 (304.45%)	|	1699.795 (101.62%)	|	1778.835 (106.35%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1123.831	|	1220.446 (108.6%)	|	2450.225 (218.02%)	|	1214.91 (108.1%)	|	851.809 (75.8%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1272.352	|	1552.121 (121.99%)	|	3209.53 (252.25%)	|	1424.327 (111.94%)	|	1075.553 (84.53%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1387.446	|	1612.006 (116.19%)	|	3408.234 (245.65%)	|	1456.395 (104.97%)	|	1153.292 (83.12%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	2494.001	|	2014.839 (80.79%)	|	5374.332 (215.49%)	|	2248.747 (90.17%)	|	1945.117 (77.99%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	2535.755	|	2619.602 (103.31%)	|	6258.396 (246.81%)	|	1834.605 (72.35%)	|	1917.428 (75.62%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	2545.247	|	2168.861 (85.21%)	|	6585.957 (258.76%)	|	1856.38 (72.94%)	|	2095.034 (82.31%) |

## EishayParseBinaryAutoType
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	fastjson2JSONB_autoTypeFilter	|	hessian	|	javaSerialize |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1464.122	|	1377.288 (94.07%)	|	289.896 (19.8%)	|	47.23 (3.23%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1912.612	|	1655.282 (86.55%)	|	250.515 (13.1%)	|	48.447 (2.53%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	2166.687	|	1839.018 (84.88%)	|	261.785 (12.08%)	|	54.281 (2.51%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1180.252	|	1145.711 (97.07%)	|	206.14 (17.47%)	|	41.565 (3.52%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1601.398	|	1552.567 (96.95%)	|	194.633 (12.15%)	|	36.416 (2.27%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1665.716	|	1560.809 (93.7%)	|	185.514 (11.14%)	|	39.72 (2.38%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	2541.012	|	2377.203 (93.55%)	|	391.545 (15.41%)	|	58.265 (2.29%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	3135.924	|	2856.19 (91.08%)	|	381.992 (12.18%)	|	58.233 (1.86%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	3196.433	|	2946.155 (92.17%)	|	345.293 (10.8%)	|	67.088 (2.1%) |

## EishayParseString
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1300.943	|	987.837 (75.93%)	|	512.557 (39.4%)	|	435.769 (33.5%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1213.728	|	911.105 (75.07%)	|	475.197 (39.15%)	|	439.408 (36.2%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1309.687	|	1283.108 (97.97%)	|	510.334 (38.97%)	|	445.659 (34.03%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	923.737	|	745.361 (80.69%)	|	382.796 (41.44%)	|	349.765 (37.86%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1115.587	|	809.813 (72.59%)	|	406.937 (36.48%)	|	378.563 (33.93%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1125.776	|	774.396 (68.79%)	|	415.458 (36.9%)	|	329.115 (29.23%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1829.514	|	1525.2 (83.37%)	|	748.486 (40.91%)	|	673.41 (36.81%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1861.372	|	1407.626 (75.62%)	|	702.482 (37.74%)	|	750.84 (40.34%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1896.136	|	2000.204 (105.49%)	|	669.733 (35.32%)	|	728.905 (38.44%) |

## EishayParseStringPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	927.971	|	269.742 (29.07%)	|	487.036 (52.48%)	|	412.207 (44.42%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	890.589	|	241.771 (27.15%)	|	439.949 (49.4%)	|	398.89 (44.79%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	929.046	|	297.502 (32.02%)	|	460.214 (49.54%)	|	414.833 (44.65%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	731.592	|	216.676 (29.62%)	|	345.738 (47.26%)	|	324.737 (44.39%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	777.75	|	226.13 (29.07%)	|	348.362 (44.79%)	|	324.162 (41.68%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	771.474	|	247.8 (32.12%)	|	378.98 (49.12%)	|	325.861 (42.24%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1461.927	|	422.411 (28.89%)	|	686.794 (46.98%)	|	621.718 (42.53%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1587.246	|	362.192 (22.82%)	|	612.471 (38.59%)	|	652.933 (41.14%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1597.042	|	437.242 (27.38%)	|	625.223 (39.15%)	|	680.968 (42.64%) |

## EishayParseTreeString
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	984.104	|	516.167 (52.45%)	|	529.544 (53.81%)	|	343.411 (34.9%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	860.379	|	389.484 (45.27%)	|	456.355 (53.04%)	|	313.505 (36.44%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1068.564	|	558.02 (52.22%)	|	515.856 (48.28%)	|	323.652 (30.29%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	549.572	|	318.146 (57.89%)	|	296.979 (54.04%)	|	258.842 (47.1%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	777.452	|	361.179 (46.46%)	|	370.298 (47.63%)	|	298.047 (38.34%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	800.239	|	404.918 (50.6%)	|	381.79 (47.71%)	|	304.46 (38.05%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1377.527	|	697.396 (50.63%)	|	744.399 (54.04%)	|	555.129 (40.3%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1512.765	|	541.593 (35.8%)	|	712.37 (47.09%)	|	573.675 (37.92%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1483.582	|	766.829 (51.69%)	|	782.967 (52.78%)	|	537.127 (36.2%) |

## EishayParseTreeStringPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	783.169	|	438.93 (56.05%)	|	491.325 (62.74%)	|	324.513 (41.44%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	679.627	|	352.311 (51.84%)	|	435.293 (64.05%)	|	306.514 (45.1%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	782.457	|	474.805 (60.68%)	|	463.292 (59.21%)	|	299.719 (38.3%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	490.371	|	273.653 (55.81%)	|	270.151 (55.09%)	|	242.967 (49.55%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	628.566	|	281.813 (44.83%)	|	342.398 (54.47%)	|	284.423 (45.25%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	634.665	|	363.762 (57.32%)	|	350.605 (55.24%)	|	270.01 (42.54%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1222.099	|	643.267 (52.64%)	|	674.287 (55.17%)	|	522.948 (42.79%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1076.624	|	418.367 (38.86%)	|	661.616 (61.45%)	|	534.681 (49.66%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1170.184	|	677.099 (57.86%)	|	716.281 (61.21%)	|	498.921 (42.64%) |

## EishayParseTreeUTF8Bytes
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	871.986	|	439.146 (50.36%)	|	601.556 (68.99%)	|	317.564 (36.42%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	783.998	|	357.527 (45.6%)	|	508.853 (64.9%)	|	312.556 (39.87%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	977.061	|	474.145 (48.53%)	|	582.13 (59.58%)	|	319.181 (32.67%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	546.877	|	255.641 (46.75%)	|	325.694 (59.56%)	|	240.374 (43.95%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	740.021	|	331.964 (44.86%)	|	422.527 (57.1%)	|	298.146 (40.29%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	770.272	|	305.616 (39.68%)	|	483.52 (62.77%)	|	290.15 (37.67%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1366.295	|	632.068 (46.26%)	|	895.375 (65.53%)	|	588.857 (43.1%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1390.472	|	514.383 (36.99%)	|	884.542 (63.61%)	|	570.308 (41.02%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1425.264	|	680.639 (47.76%)	|	859.228 (60.29%)	|	543.899 (38.16%) |

## EishayParseTreeUTF8BytesPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	651.492	|	368.652 (56.59%)	|	537.145 (82.45%)	|	290.2 (44.54%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	627.661	|	307.868 (49.05%)	|	487.5 (77.67%)	|	291.605 (46.46%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	757.994	|	405.336 (53.47%)	|	509.014 (67.15%)	|	309.105 (40.78%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	486.774	|	229.337 (47.11%)	|	288.774 (59.32%)	|	224.971 (46.22%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	621.818	|	252.771 (40.65%)	|	388.576 (62.49%)	|	281.139 (45.21%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	611.293	|	275.851 (45.13%)	|	425.414 (69.59%)	|	274.041 (44.83%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1172.145	|	547.841 (46.74%)	|	811.631 (69.24%)	|	519.428 (44.31%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1138.484	|	406.988 (35.75%)	|	828.154 (72.74%)	|	564.928 (49.62%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1146.37	|	568.832 (49.62%)	|	890.179 (77.65%)	|	558.39 (48.71%) |

## EishayParseUTF8Bytes
| aliyun ecs spec | jdk version 	|	fastjson2	|	dsljson	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1103.979	|	923.506 (83.65%)	|	792.361 (71.77%)	|	599.551 (54.31%)	|	310.944 (28.17%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1066.68	|	868.894 (81.46%)	|	761.822 (71.42%)	|	531.257 (49.8%)	|	317.304 (29.75%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1146.093	|	831.271 (72.53%)	|	957.016 (83.5%)	|	553.258 (48.27%)	|	307.941 (26.87%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	796.431	|	598.875 (75.19%)	|	681.866 (85.62%)	|	407.264 (51.14%)	|	242.017 (30.39%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1004.395	|	622.313 (61.96%)	|	678.291 (67.53%)	|	466.963 (46.49%)	|	289.513 (28.82%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	934.277	|	594.641 (63.65%)	|	542.682 (58.09%)	|	452.449 (48.43%)	|	284.069 (30.41%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1380.068	|	1025.594 (74.31%)	|	1474.618 (106.85%)	|	1007.086 (72.97%)	|	597.816 (43.32%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1665.806	|	835.762 (50.17%)	|	1298.885 (77.97%)	|	890.27 (53.44%)	|	572.494 (34.37%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1563.179	|	802.412 (51.33%)	|	1676.182 (107.23%)	|	827.797 (52.96%)	|	540.404 (34.57%) |

## EishayParseUTF8BytesPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	835.415	|	246.932 (29.56%)	|	529.769 (63.41%)	|	296.248 (35.46%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	845.503	|	225.574 (26.68%)	|	489.818 (57.93%)	|	297.92 (35.24%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	861.785	|	275.973 (32.02%)	|	483.069 (56.05%)	|	307.701 (35.71%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	676.551	|	206.752 (30.56%)	|	365.389 (54.01%)	|	225.082 (33.27%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	757.626	|	197.344 (26.05%)	|	417.496 (55.11%)	|	276.267 (36.46%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	771.399	|	185.205 (24.01%)	|	361.191 (46.82%)	|	276.126 (35.8%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1173.144	|	431.563 (36.79%)	|	908.13 (77.41%)	|	517.222 (44.09%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1415.895	|	351.448 (24.82%)	|	774.486 (54.7%)	|	569.479 (40.22%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1404.669	|	411.809 (29.32%)	|	756.051 (53.82%)	|	557.736 (39.71%) |

## EishayWriteBinary
| aliyun ecs spec | jdk version 	|	fastjson2UTF8Bytes	|	hessian	|	javaSerialize	|	jsonb |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1527.098	|	342.951 (22.46%)	|	226.481 (14.83%)	|	1940.557 (127.07%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1564.422	|	338.528 (21.64%)	|	217.559 (13.91%)	|	2437.52 (155.81%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1928.333	|	325.511 (16.88%)	|	223.387 (11.58%)	|	3294.978 (170.87%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1325.459	|	353.131 (26.64%)	|	207.085 (15.62%)	|	1664.222 (125.56%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1414.594	|	351.145 (24.82%)	|	222.661 (15.74%)	|	2162.359 (152.86%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1428.608	|	343.442 (24.04%)	|	210.994 (14.77%)	|	2197.203 (153.8%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	2897.774	|	636.394 (21.96%)	|	435.803 (15.04%)	|	3641.23 (125.66%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	3135.596	|	691.807 (22.06%)	|	429.985 (13.71%)	|	4893.173 (156.05%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	3106.95	|	676.013 (21.76%)	|	448.601 (14.44%)	|	4879.785 (157.06%) |

## EishayWriteBinaryArrayMapping
| aliyun ecs spec | jdk version 	|	fastjson1UTF8Bytes	|	fastjson2UTF8Bytes	|	jsonb	|	kryo	|	protobuf |
|-----|-----|----------|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	762.741	|	1861.678 (244.08%)	|	3095.395 (405.83%)	|	1894.575 (248.39%)	|	1451.017 (190.24%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	709.39	|	2080.037 (293.21%)	|	4274.07 (602.5%)	|	1997.361 (281.56%)	|	1650.42 (232.65%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	697.708	|	2183.472 (312.95%)	|	5715.994 (819.25%)	|	2055.144 (294.56%)	|	1749.845 (250.8%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	498.026	|	1528.776 (306.97%)	|	2577.552 (517.55%)	|	1468.005 (294.76%)	|	905.451 (181.81%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	484.559	|	1734.46 (357.95%)	|	4192.55 (865.23%)	|	1585.866 (327.28%)	|	1435.164 (296.18%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	505.319	|	1684.46 (333.35%)	|	4227.105 (836.52%)	|	1553.654 (307.46%)	|	1369.885 (271.09%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1151.494	|	3218.941 (279.54%)	|	5766.064 (500.75%)	|	2540.023 (220.58%)	|	2195.8 (190.69%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1054.792	|	3418.833 (324.12%)	|	8880.936 (841.96%)	|	2893.985 (274.37%)	|	2256.734 (213.95%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1082.023	|	3391.745 (313.46%)	|	9651.021 (891.94%)	|	3015.44 (278.69%)	|	2462.824 (227.61%) |

## EishayWriteBinaryAutoType
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	fastjson2UTF8Bytes	|	hessian	|	javaSerialize |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1286.631	|	1453.972 (113.01%)	|	336.239 (26.13%)	|	228.519 (17.76%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1413.414	|	1531.745 (108.37%)	|	334.237 (23.65%)	|	203.033 (14.36%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1701.98	|	1820.719 (106.98%)	|	324.698 (19.08%)	|	213.834 (12.56%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1108.787	|	1283.441 (115.75%)	|	351.778 (31.73%)	|	207.442 (18.71%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1334.679	|	1337.966 (100.25%)	|	357.464 (26.78%)	|	220.146 (16.49%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1076.151	|	1291.31 (119.99%)	|	323.948 (30.1%)	|	210.428 (19.55%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	2507.154	|	2827.079 (112.76%)	|	628.476 (25.07%)	|	415.477 (16.57%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	2869.655	|	3075.427 (107.17%)	|	687.169 (23.95%)	|	441.877 (15.4%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	2897.829	|	3039.042 (104.87%)	|	679.56 (23.45%)	|	445.99 (15.39%) |

## EishayWriteString
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1617.183	|	614.846 (38.02%)	|	967.085 (59.8%)	|	442.235 (27.35%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1483.852	|	586.997 (39.56%)	|	938.092 (63.22%)	|	363.761 (24.51%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1617.466	|	628.956 (38.89%)	|	1032.857 (63.86%)	|	250.382 (15.48%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1220.405	|	483.221 (39.6%)	|	651.29 (53.37%)	|	371.023 (30.4%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1309.678	|	462.748 (35.33%)	|	738.485 (56.39%)	|	256.498 (19.58%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1312.936	|	535.286 (40.77%)	|	694.609 (52.91%)	|	225.062 (17.14%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	2959.598	|	1161.786 (39.25%)	|	1738.403 (58.74%)	|	764.753 (25.84%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	2888.283	|	1096.986 (37.98%)	|	1645.901 (56.99%)	|	658.732 (22.81%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	2896.307	|	1257.364 (43.41%)	|	1767.987 (61.04%)	|	561.367 (19.38%) |

## EishayWriteStringTree
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1200.98	|	832.427 (69.31%)	|	958.756 (79.83%)	|	489.784 (40.78%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1235.305	|	777.375 (62.93%)	|	940.125 (76.1%)	|	377.906 (30.59%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	941.885	|	588.088 (62.44%)	|	677.586 (71.94%)	|	401.993 (42.68%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1095.766	|	617.288 (56.33%)	|	728.273 (66.46%)	|	355.446 (32.44%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1059.8	|	650.73 (61.4%)	|	673.68 (63.57%)	|	227.022 (21.42%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1902.119	|	1296.067 (68.14%)	|	1575.264 (82.82%)	|	847.135 (44.54%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1949.3	|	1244.435 (63.84%)	|	1535.103 (78.75%)	|	698.38 (35.83%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1905.051	|	1286.035 (67.51%)	|	1407.61 (73.89%)	|	562.818 (29.54%) |

## EishayWriteStringTree1x
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1046.941	|	768.318 (73.39%)	|	872.111 (83.3%)	|	475.441 (45.41%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1089.208	|	762.04 (69.96%)	|	907.277 (83.3%)	|	374.578 (34.39%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	823.537	|	554.828 (67.37%)	|	617.044 (74.93%)	|	392.242 (47.63%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	916.581	|	560.435 (61.14%)	|	706.307 (77.06%)	|	332.451 (36.27%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	769.99	|	553.471 (71.88%)	|	643.528 (83.58%)	|	214.149 (27.81%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	1720.011	|	1188.629 (69.11%)	|	1479.519 (86.02%)	|	808.465 (47%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	1771.42	|	1196.68 (67.55%)	|	1485.32 (83.85%)	|	688.037 (38.84%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	1475.633	|	1126.216 (76.32%)	|	1308.993 (88.71%)	|	556.545 (37.72%) |

## EishayWriteUTF8Bytes
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1508.263	|	578.5 (38.36%)	|	921.479 (61.1%)	|	381.152 (25.27%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1609.011	|	546.073 (33.94%)	|	861.262 (53.53%)	|	356.8 (22.18%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1321.337	|	482.774 (36.54%)	|	681.434 (51.57%)	|	314.123 (23.77%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1418.021	|	510.907 (36.03%)	|	649.705 (45.82%)	|	286.349 (20.19%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1433.226	|	488.716 (34.1%)	|	655.895 (45.76%)	|	208.507 (14.55%) |
| MacBookPro M1 Pro | zulu-jdk-8.66.0.15_aarch64	|	2891.78	|	1027.458 (35.53%)	|	1590.502 (55%)	|	652.731 (22.57%) |
| MacBookPro M1 Pro | zulu-jdk-11.60.19_aarch64	|	3138.575	|	981.409 (31.27%)	|	1403.927 (44.73%)	|	660.125 (21.03%) |
| MacBookPro M1 Pro | oracle-jdk-17.0.5_aarch64	|	3097.907	|	976.922 (31.53%)	|	1528.656 (49.34%)	|	556.62 (17.97%) |
