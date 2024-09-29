**Test Result Report on testing activities from 6/19/2024 to 6/28/2024.**

From 6/19/2024 to 6/21/2024 Release of the 1st build. Our team performed **smoke testing**:

**Environment:**

**FirstPerson**: Windows 11; Google Chrome v. v.125.0.6422.176

**SecondPerson**: Windows 11 Pro; Opera v. 111.0.5168.25

**ThirdPerson**: Windows 11; Microsoft Edge v.126.0.2592.61

**ForthPerson**: Windows 10 Pro; Microsoft Edge v.126.0.2592.61

**FifthPerson**: Windows 11; Mozilla Firefox v. 127.0.1

**SixthPerson**: macOS  Monterey v.12.6.2; Safari v. 15.6.1

![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.001.png)

![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.002.png)













List of bugs found

|**Jira link**|**Priority**|
| :- | :- |
|5454|Medium|
|5452|Medium|
|5447|Critical|
|5395|Major|
|5394|Medium|
|5393|Critical|
|5392|Major|
|5391|Medium|
|5390|Critical|
|5389|Medium|
|5388|Critical|
|5387|Medium|
|5386|Major|
|5385|Medium|
|5384|Medium|
|5383|Low|
|5382|Critical|
|5381|Critical|
|5380|Low|

Then from 6/24/2024 to 6/28/2024 we were working on stories individually. 

**My environment**:

Windows 11 Pro, Google Chrome v.125.0.6422.176

Windows 11 Pro, Opera v.111.0.5168.25 

**User Stories**:

1. https://xxx/jira/browse/xxxx-4949

![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.003.png)

![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.004.png)

List of bugs found:

|**Jira link**|**Priority**|
| :- | :- |
|5381|Critical|
|5382|Critical|
|5411|Critical|
|5415|Critical|
|5416|Critical|
|5417|Critical|
|5419|Critical|
|5424|Critical|
|5413|Major|
|5412|Medium|
|5414|Medium|
|5408|Low|

1. https://xxxx/jira/browse/xxx-4953


![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.005.png)

![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.006.png)

List of bugs found

|**Jira link**|**Priority**|
| :- | :- |
|5475|Medium|
|5474|Low|


1. https://xxx/jira/browse/xxx-4957

![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.007.png)

![](Aspose.Words.a4b4aa14-d7d1-4295-a914-db0c218a2ec4.008.png)

List of bugs found

|**Jira link**|**Priority**|
| :- | :- |
|5477|Medium|
|5480|Low|

**Overall notes and recommendations:**

As we can see current **quality** of the build is **low** as **80%** of smoke tests **failed** resulted in **19 bugs**. As for story https://xxx/jira/browse/xxx-4949 it’s quality is low as **63%** of tests failed and the biggest part connected to the edge cases while validating text fields(<max,<min,>max,>min limits; ). There are serious issues with fields’ validation and inability to upload photos that blocks viewing them. In https://xxx/jira/browse/xxx-4953 situation is better as there are only low/medium defects mostly related to ‘items per page’ dropdown and in general pagination navigation works. As for https://xxxx/jira/browse/xxx-4957 it couldn’t be tested mostly and no test case was passed as bugs derived from inability to upload any photos. Also need to fix sorting both albums and photos by upload date as well as giving hint of the album by hovering over the album cover. The current build **isn’t ready to be deployed** as main functionalities have critical bugs.



