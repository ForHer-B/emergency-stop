---
{"dg-publish":true,"permalink":"/presentable-state/","tags":["gardenEntry"]}
---


Link to Drive (All Markdown Documents + PDF) : https://drive.google.com/drive/folders/1iN1xTIpAH9hCwa0uEKYq43PEeO2Rn3x0?usp=sharing
Best Idea would be to download the drive and open the "Presentable state" Document in Obsidian so that all PDFs are linked and references (links below) point you to the exact relevant paragraph selected.

---

[[AGV application safety issues research.pdf#page=5&selection=46,0,61,38|AGV application safety issues research, page 5]]
Warning Lights 
- a visible safety parameter of the tow truck's area of operation [[Design, evaluation and possible alternatives for.pdf#page=9&selection=32,0,32,32|Design, evaluation and possible alternatives for, page 9]]
- turning signals to depict future movement
Audible warning signals 
- Acknowledgment/operational signal which is a slow repetitive signal
- Alarm signal when there is a dangerous situation/ error
Emergency stop on the AGV
- 2 Provided on each AGV
- Actuator for emergency stop device should be easily visible and accessible [[Design, evaluation and possible alternatives for.pdf#page=9&selection=32,0,32,32|Design, evaluation and possible alternatives for, page 9]]
- "If the truck has a specified operator position with controls, an emergency stop device shall be fitted near these controls." It should also be within the UI and Dashboard. The stop should NOT be on the touchscreen (if there is one) but still a physical button. [[Industrial trucks  Safety requirements and verification -- 2 -- 93e092977c93b98988761e90f111b8c7 -- Anna’s Archive.pdf#page=24&selection=69,0,71,20|Industrial trucks  Safety requirements and verification -- 2 -- 93e092977c93b98988761e90f111b8c7 -- Anna’s Archive, page 24]] https://www.controldesign.com/safety/safety-components/article/21526010/standards-guide-the-use-of-e-stops?utm_source=chatgpt.com


![Pasted image 20250223180328.png](/img/user/images/Pasted%20image%2020250223180328.png)
In this AGV, the emergency stop consists of 2 accessible buttons on the vehicle. They are both equal but independent of one another. 
We could do the same for the tow truck. 
Buttons used for the emergency stop, clearly visible and easy to press.
![Pasted image 20250223180511.png](/img/user/images/Pasted%20image%2020250223180511.png)
![Pasted image 20250223180747.png](/img/user/images/Pasted%20image%2020250223180747.png)


Remote Emergency stops
Since there is no real information about adding emergency stops to the environment, we can  add them in these places:
- Fire alarms
- Entry and Exit Points
- High-Traffic Intersections where there is a higher chance of collision
- Workstations and Assembly Lines to ensure that any team member can access it
- Load Transfer Areas: In areas where load transfer operations create potential hazards [[Design, evaluation and possible alternatives for.pdf]]
- In areas where operators interact with the AGV (currently the area where we are attaching and detaching dollies and charging area). [[Industrial trucks  Safety requirements and verification -- 2 -- 93e092977c93b98988761e90f111b8c7 -- Anna’s Archive.pdf]]




Future thinking to do from the readings I did: 
- Dynamic safety field switch according to speed (future issue) but this gives the idea that we may need to either lower our speed depending on where we are (more change of people is inside)) [[Design, evaluation and possible alternatives for.pdf#page=15&selection=117,0,132,68|Design, evaluation and possible alternatives for, page 15]]
- We should also have routine checks on not just the sensors, the hardware and overall health but of the safety system as well.
- A basic requisite common to all categories is that the SRP/CS must be designed to resist the normal operating stresses and the influence of predictable disturbances (dust, chips. . . ) and external influences like vibration or electromagnetic interference. [[Design, evaluation and possible alternatives for.pdf#page=19&selection=51,0,55,70|Design, evaluation and possible alternatives for, page 19]]
- We should also have routine checks on not just the sensors, the hardware and overall health but of the safety system as well.
- We might want to either have a larger FOV by camera or simply slow down at turns. (Future issue)[[Design, evaluation and possible alternatives for.pdf#page=59&selection=32,0,34,34|Design, evaluation and possible alternatives for, page 59]]


