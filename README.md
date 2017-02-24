
# THE CHALLENGE
Dive Operations at the Georgia Aquarium manages all diving activities of the 120  volunteers and staff. A dive log is necessary for  the purposes of safety and record keeping. This log may contain information such as date,  time, location, dive profile, conditions, and divers. It can provide data important in day-to-day aquarium operations, as well as valuable data in case of a diving accident.  

# GOALS
To create an intuitive and convinient dive-logging tablet application.
* Allow for management of divers, training, and other information
* Have a better and more usable design that reduces user resistance

# APPROACH/STRATEGY
Applying Google Venture's "Sprint Methodology" to our 3-week project

### Day 0: Learning Sprint

* A teammate introduced the book, "Sprint", by Jake Knapp, as a way to streamline our approach
* We have 3 weeks to work on project and wanted to compress our workflow via Sprint Methodology to "Fail fast, fail often" to "learn fast, learn often."
* We also came up with questions to ask our stakeholders. To do this, I thought about doing some research to be competent on the subject but as a team we figured it's best not to research ... this way, our questions would be purely unbiased because we truly aren't SME's in the diving field.

** Get the gist via this Google Talk: https://www.youtube.com/watch?v=aWQUSiOZ0x8
http://www.gv.com/sprint/

### Day 1: Meeting the Stakeholders

* Met with stakeholders to discuss the pain points and what they envision the ultimate goal to be: "to make an easy to use dive log tablet app"
* We got a workflow of how the current process goes: 
1. Getting tasks from the "Tender"
2. Then after divers are done, fill out dive logs into paper form, then into the computer.

* We then made a mind map of the problems and phrased them in the form of "how might we solve [insert problem]"
* Ended day with creating competitive analysis with similar tools



### Day 2: Consolidating notes

* We put our notes together to get a better understanding of what we need to do with the project.

### Day 3: Conceptualizing our app

* Invidually, we made our own variations of how the app should look like based on our findings. We then gave each other feedback on what was great or not, then proceeded on to merging our ideas together.


### Day 4: Visit to the field

* Met the multiple users of the current app to get better insight on their pain points.
* Asked them further questions to get a better understanding of their current workflow.
* Asked the main stakeholder what ideal features he would like to see in the app.

### Day 5: Sketches & Prototype
* Mapped out 2 user flow journeys (OV/Guests and Mammals)
* Had a victory with how to info. architech the diver fields (nest time in/out under diver name, while the start/end PSI are separate boxes along the same field)
* Got a clickable prototype working with Invision

---
# PROCESS/RESEARCH
### Remaining 2 weeks
After the first week, we went with the more traditional UX process of constant iterations. We would discuss the pain points and new information gathered from the user tests, come up with ways to compartmentalize fields or information, run more user-tests, redo the designs, create the prototypes, and user test again. The very last thing we did was focus on aesthetics and the style-guide — this would make the prototype more "app-like" and provide a sense of polish.

## Insight/Victories
1. Removed scroll-directory of divers because people rarely scroll through thousands of divers to find a person. Instead, we replaced it with a “add diver” button with auto-complete text.
2. Consolidated “time in/out” into diver field to establish its relationship to diver ...rather than time being an independent component.
3. Error handling with Inventory Checklist: (bold the items that have been initially entered ...upon checkout, the non-applicable items are greyed out. Plus, orange rectangles will act as error handling clues).

# RESULT

# WHAT I LEARNED
* Even with small changes like how to handle a selection element (to make it a dropdown, scroll, toggle button) would take a whole afternoon of discussion. Though it can be frustrating and cause a lot of heat, we learned not to take the matter too personal as it's more of learning to reason the "why's" behind the design that make it so much more worth it. For example, when discussing the Air/Trimix as a scrollable toggle instead of a dropdown, because it was so unique to a certain flow that didn't conform to the rest of our design, we decided to treat it as the abnormality because we wanted users to know it was a special case for a special user flow.
