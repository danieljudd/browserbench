# browserbench

Benchmarks for browsers that are minimal/privacy focused.
All tests within RAM range, and no throttling of CPU, same PC.

Best of each test:
- basemark: ungoogled chrome (1174.43) mean:895
- html5test: ungoogled chrome (535) mean:511
- speedbattle: waterfox/firefox, re-ran a few times and waterfox would jump a little higher overall (1913.86) mean:1632
- jetstream: ungoogled chrome (115.579) mean:94.3

Conclusion:
Firefox is probably the best non-google browser tested. It is not worth using waterfox for speed or features (given that it is based off firefox 68). Waterfox is expecting to be shutting features off for privacy reasons, affecting feature tests.

Ungoogled Chrome is very unspecial and a version behind, but fast. Brave is great at the tests but holds the most anti-privacy features of all the browsers.

Need more research...

### Tests:

## https://web.basemark.com (13/02/20)

1. desktop using Windows 10.0 with Firefox 73.0 score: (with privacy addons)
745.5

Conformance
CSS Capabilities
57.27%

HTML5 Capabilities
92.97%

Page Load and Responsiveness Capabilities
99.43%

Resize Capabilities
75.86%


2. desktop using Windows 10.0 with Chrome 79.0.3945.130 (ungoogled chromium from https://chocolatey.org/packages/ungoogled-chromium) score: 
1174.43

Conformance
CSS Capabilities57.75%

HTML5 Capabilities96.58%

Page Load and Responsiveness Capabilities98.43%

Resize Capabilities75.97%


3. desktop using Windows 10.0 with Chrome 80.0.3987.87 (brave) score:
1011.4 

CSS Capabilities57.75%

HTML5 Capabilities95.5%

Page Load and Responsiveness Capabilities96.23%

Resize Capabilities75.97%

4. desktop using Windows 10.0 with Firefox 68.0 score: (waterfox)
648.74

Conformance
CSS Capabilities
56.79%

HTML5 Capabilities
91.17%

Page Load and Responsiveness Capabilities
97.65%

Resize Capabilities
75.86%

## https://html5test.com/
- waterfox: 501 out of 555 points
- brave: 531 OUT OF 555 POINTS
- ungoogled chrome: 535 OUT OF 555 POINTS
- firefox: 513 out of 555 points
- firefox private tab: 499 out of 555 points

## http://www.speed-battle.com/speedtest_e.php

overall scores:

- ungoogled chromium: 1250.35
- firefox: 1862.65
- brave: 1501.29
- waterfox: 1913.86

## https://browserbench.org/JetStream/

overall scores:

- firefox: 74.941
- brave: 106.540
- waterfox: 80.317
- ungoogled chrome: 115.579

