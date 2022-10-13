Tested website: Healthinfobd
I have completed performance test on frequently used API for the website Healthinfobd run in non-GUI mode.
Test executed for the below mentioned scenario.
12 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 18 And Total Concurrent API requested: 1714.
15 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 28 And Total Concurrent API requested: 2117.
23 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 34 And Total Concurrent API requested: 3246.
25 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 28 And Total Concurrent API requested: 3537.
28 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 41 And Total Concurrent API requested: 3969.
While executed 28 concurrent request, found  43 request got connection timeout and error rate is 1.08%. 
Summary: Server can handle almost concurrent 3681 API call with less than 1% error rate.
