Smart watches can record our exercise status, monitor our heart rate, etc. Therefore, through the smart watch, we can check how much we walked, how far we walked, and how many calories we burned.

There is a widely circulated view that walking 10,000 steps a day is enough. Is that true? It seems to be different from our body. Sometimes it feels easy to see that I have walked 10,000 steps on the smart watch, and sometimes I have not reached 10,000 steps after a lot of effort. Why is this happening?

According to research, the number of steps produced by walking in daily life does not contribute much to fitness. Only serious exercise can have an effect, that is, walking for a certain time and reaching a certain speed can achieve the effect of fitness. Therefore, the number of steps given by the smart watch is not all valid. It is necessary to know the effective number of steps during serious exercise to accurately understand the actual amount of exercise for fitness.

According to WHO's recommendations, adults aged 18–64 should do at least 150 minutes of moderate-intensity aerobic physical activity throughout the week or do at least 75 minutes of vigorous-intensity aerobic physical activity throughout the week or an equivalent combination of moderate- and vigorous-intensity activity. However, based on the number of steps, floors, distance, and calories given by the smart watch, it seems difficult for us to judge whether the current amount of exercise meets the standard.

Based on the above problems, ActFace proposed a solution to use an intuitive method to evaluate the amount of exercise, specifically to score the amount of exercise. Like student exams, the score range is 0-100. If the score is less than 60, it means that the amount of exercise is not enough; 60-85 is qualified and the amount of exercise is up to the standard; 85-95 is good, and the exercise is relatively good; 95-100 is excellent, indicating that exercise Very well. Over 100 points means excessive exercise and should be avoided.

The design idea of ActFace is explained below.

## 1. Functions of smart watches
Since it is a watch, of course the primary function is Watch time. You can know the year, month, day, hour, minute, second, and day of the week when you lift your wrist.

Since there is smart, then you need to have functions that traditional watches don’t have, such as exercise monitoring, physical condition monitoring, environmental monitoring, etc. The use of smart functions depends on specific usage scenarios, such as office or home, walking, mountain climbing, hiking, etc. The functional requirements of each scenario are different.

Other functions, such as information reception, music playback control, etc., are too tightly associated with the mobile phone and are rather tasteless, so I will not discuss them here.

## 2. Functional requirements for smart watches in different usage scenarios
As mentioned earlier, the scenarios for using smart watches include: office or home, walking, climbing, hiking, etc.

### Office or home scene
In this scenario, smart watches can be mainly used to monitor heart rate and sedentary time to prevent inactivity from affecting health.
For garmin watches, there are the following functions to meet the demand:
- Heart rate
- MoveBar

### Walking scene
In this scenario, the main purpose is to monitor the movement and understand the amount of exercise, to achieve better fitness results.

The functions that garmin watches can be used in walking scenes include:
- Number of steps
- Floors
- Walking distance
- calories

According to research, the number of steps produced by walking in daily life does not contribute much to fitness. Only serious exercise can have an effect, that is, walking for a certain period of time can achieve the effect of fitness. Therefore, the number of steps given by the smart watch is not all valid. It is necessary to know the effective number of steps during serious exercise to accurately understand the actual amount of exercise for fitness. That is, when walking, you also need to know:
- Effective exercise steps
- Effective exercise time
- Effective exercise walking distance

### Hiking, climbing scene
In the scenario of hiking and mountain climbing, smart watches are mainly used to monitor the amount of exercise and environmental changes. Such as walking, rest time, altitude change, weather, etc.

The functions that garmin watches can be used in mountaineering/hiking scenes include:
- Distance traveled
- altitude

The following functions need to be added to meet the needs of mountaineering/hiking scenes:
- Ascent and descent altitude
- Ascent and descend time
- Time and frequency of rest
- Climbing/Hiking travel time
- The highest/lowest altitude reached
- Weather conditions
- Sunrise/sunset time

## 3. Requirements for the operation and use of smart watches
The ideal application should not require user intervention and will not disturb the user. It works silently in the background, automatically perceives, and automatically gives the information that the user needs.

Garmin watches divide applications into Watch Faces, Data Fields, Device Apps and Widgets. Each application type has its own specific usage.

Garmin watches provide many functions, these functions are present in a variety of different watch faces, data fields, applications and plugins. For example, running, hiking, and climbing functions are three different applications, Need to switch between different applications when using. Due to the limitation of the size of the watch and the way of using it-physical buttons or touch screen-it is very inconvenient to perform frequent operations on the watch.

Human-computer interaction researchers believe that the best human-computer interface is no interface. The watch should automatically sense the user's current exercise status, such as: walking, running, climbing, resting, etc. Through intelligent situation awareness, all commonly used functions can be concentrated on one interface, and you can see the desired information, such as date and time, sports status, sports environment conditions, etc., instead of allowing users to switch between different application to get these information.

Generally speaking, the fixed interface of the watch is Watch Face, so it is best to display all sports and environmental information, as well as the date and time on one Watch Face.

## 4. Functional design of ActFace
- The first is to display the time. The main function of the watch is watch the time. A watch that cannot read the time at a glance is not a watch.

- The second is to display the status of the watch, know the power of the watch in order to charge it in time, and know the connection status of the watch and the mobile phone in order to know whether the online information displayed on the watch is updated in time.

- Exercise information is also the key point that needs to be displayed. Although data such as steps, floors, distance, and calories can also be used to evaluate the amount of exercise, but it is not intuitive and a direct method to give the amount of exercise is required. My method is to score the amount of exercise, 0-100. Like student exams, if you fail to reach 60 points, you are fail, indicating that your exercise is not enough; 60-85 is passing, and your exercise has just reached the standard; 85-95 is good, indicating the exercise is good; 95-100 is excellent, indicating that you are exercising very well. Over 100 points means excessive exercise and should be avoided.

- In addition, in the different scenarios mentioned above, the focus of each scenario is different, and the data that needs to be known is also different.
> - In office/home, if you Need to avoid sedentary sitting, you must use Movebar;
> - When walking, you need to know the number of steps you walk, walking time, walking distance, etc. This information should not include data generated by casual walking in daily life. These data can be obtained by calculation: effective exercise steps, effective exercise time, effective exercise walking distance;
> - When hiking and mountaineering, you need to know: the highest/lowest altitude reached, the ascent and descent altitude, the time used for ascending and descending, the time and number of climbing/hiking breaks, the climbing/hiking travel time, etc., All data are  obtained by calculation;

- The body and environmental information that needs to known varies according to the scenario. Generally speaking, heart rate and weather conditions are more important and need to be checked in all scenarios. In hiking and mountain climbing scenarios, the current altitude, sunrise and sunset times are also important.

## 5. ActFace Watch Face
There are two versions, ActFace is a digital Watch Face and ActFaceA is analog  Watch Face. The current analog Watch Face version is relatively full of functions, and the ActFace digital Watch Face does not yet have some functions required for hiking and mountaineering scenes. Both versions can be downloaded from Garmin Connect IQ Store.

– ActFace：https://apps.garmin.com/en-US/apps/937c158b-2eaa-44e6-b30f-9e77c222969e
– ActFaceA：https://apps.garmin.com/en-US/apps/3078abc4-c567-4bbb-82ca-c52b6a3d5ba3#0
