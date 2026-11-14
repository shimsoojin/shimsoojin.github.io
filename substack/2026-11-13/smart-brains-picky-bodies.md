TITLE: Smart Brains, Picky Bodies
SUBTITLE: five robot stories from one week, and the thread between them

[COVER IMAGE — Soojin inserts]
*Rachel Whiteread, House, 1993*

---

Robots got easier to teach this week.

Where they should live got harder to answer.

I posted five stories on Instagram this week. Two were about robots moving into our homes, two were about robot brains, and one was about a robot body. Read them side by side and a pattern shows up: the brain is turning into something you can license, while the body still has to be built for one place.

*Personal notes, not the companies' official views.*

## Amazon's second knock on the front door

**What happened:** Amazon is reportedly building a new home robot after Astro, [per CNBC](https://www.cnbc.com/2026/11/08/amazon-home-robot-fauna-sprout.html). The clues are job posts for a "new-to-world robot product" that works in "dynamic home environments." The roles sit with [Fauna Robotics](https://interestingengineering.com/ai-robotics/amazon-acquires-fauna-robotics), the New York startup Amazon bought in March, maker of Sprout, a 3.5-ft humanoid sold to researchers for $50,000. No product, price, or date has been announced.

**Why it matters:** Astro launched in 2021 at $1,450, never left beta, and reached only "a few thousand" customers ([NewsBytes](https://www.newsbytesapp.com/news/science/after-astro-flop-amazon-takes-another-shot-at-home-robots/story)). A company that already runs more than a million warehouse robots is trying the house again. It is a bit like Apple's Newton before the iPhone. The first try taught them what the home actually asks for.

**My take:** I don't need a home robot that can do everything. I need one that does one boring job so well I forget it's there. Astro tried to be a friend. The next one should try to be useful first.

[Watch the 15-sec version](https://www.instagram.com/reel/Dfh3_ZTkmKc/)

## The doorbell company learns to fly

**What happened:** Ring [announced](https://www.aboutamazon.com/news/devices/ring-drone-cam-rover-cam-security-robot) the Drone Cam, an indoor security drone, at $249.99. When a Ring camera, sensor, or alarm goes off, it flies to patrol points you set, then returns to its dock with the camera off. It ships in the US on January 27, 2027, pending FCC authorization. A rolling sibling, Rover Cam ($999.99), is for businesses.

**Why it matters:** The drone is only smart enough to fly and land. The mapping, room recognition, and route planning live in the cloud, in what Ring calls AI Pilot. Think of a thin client: a cheap screen at your desk, the real computer somewhere else. That is how a flying robot gets to $249. It also means the hard question is not the hardware. It is who sees the footage ([TechCrunch](https://techcrunch.com/2026/11/10/ring-known-for-its-doorbell-cameras-launches-a-home-security-drone-and-an-enterprise-security-robot/) notes Ring hasn't said whether video can stay local).

**My take:** A camera that only wakes up when something is wrong is a better design than one that watches all day. But trust at home isn't a spec. It's about who holds the footage. I'd want local storage before I'd want wings.

[Watch the 15-sec version](https://www.instagram.com/reel/Dfkc5i3iHau/)

## Show it once

**What happened:** At CoRL on November 9, NVIDIA introduced GR00T 2, which it calls a "world action model" built on Cosmos ([Let's Data Science](https://letsdatascience.com/news/nvidia-unveils-gr00t-2-and-isaac-lab-30-at-corl-867274ea)). Most of its training mix is first-person human video, about 402,730 hours per [The Neuron](https://www.theneuron.ai/robotics-insider/nvidia-gr00t-2-human-video-robot-learning/). In NVIDIA's own tests across 50 tasks, it hit 71% success with one demonstration and 95% with five. It also completed 40 of the 50 tasks at least once with no task-specific demo.

**Why it matters:** Robot data has always been the bottleneck. Teleop, where a person drives the robot by hand to record each motion, is slow and expensive. Human video is everywhere. A world action model is roughly an LLM for physics: it predicts what happens next and which move gets you there. **If robots can learn from watching us, teaching a new task shrinks from a pile of recordings to a handful of demos.** These are company numbers, so I'd wait for outside tests.

**My take:** Human video teaches a robot what to do. It doesn't teach it how hard to press. Video is the eyes; teleop still carries the touch. My bet is the winners use both.

[Watch the 15-sec version](https://www.instagram.com/reel/DfnBo8tlUaQ/)

## A brain with two jobs

**What happened:** Google DeepMind released Gemini Robotics 2.5 on November 10 and showed it running Apptronik's Apollo 2 humanoid in proof-of-concept pilots at Mercedes-Benz plants in Kecskemét, Hungary, and Sindelfingen, Germany ([Interesting Engineering](https://interestingengineering.com/ai-robotics/google-gemini-robotics-2-5-humanoid-factory-trial)). On kitting, sorting parts from bulk bins into trays, it reached 96%. Across 200+ tasks, success rose 30–100% and speed 20–30%. Safety steering improved 43% near people and 33% near obstacles. The model is going to robotics partners only, not a public API.

**Why it matters:** The system splits the brain in two. Gemini Robotics ER keeps track of the workflow, step by step, like a shift lead. Gemini Robotics 2.5 is a VLA (vision-language-action model: it sees, understands the instruction, and moves) that runs the arms and hands. It is the same split as a restaurant: one person calls the orders, another plates them. **Google isn't selling a robot. It's selling the brain to whoever builds one.**

[IMAGE: diagram2-two-brains.png]
*One brain, two jobs. The shift lead decides what's next; the hands figure out how.*

**My take:** Factory first. Not because factories are more exciting, but because a factory is one job, repeated, with someone measuring it. That's where trust gets earned. Specific first, then the home.

[Watch the 15-sec version](https://www.instagram.com/reel/DfpmeV-D6P9/)

## Wheels are a test, not a product

**What happened:** Boston Dynamics posted a video on November 9 of Atlas on wheels, spinning a full 360 degrees in the air and landing ([Korea JoongAng Daily](https://www.koreajoongangdaily.com/business/atlas-is-on-a-roll-hyundais-humanoid-robot-trades-feet-for-wheels/12965255)). Per [Humanoids Daily](https://www.humanoidsdaily.com/news/boston-dynamics-atlas-wheels-rl-actuator-test), the jump worked on the first try on hardware. Controls engineer Andy Wu: "A wheeled Atlas isn't a product. It's a research testbed." Separately, Hyundai Mobis said it starts making Atlas actuator prototypes this month at its Uiwang research center, with expected supply timing of 2028 ([MoneyToday](https://www.mt.co.kr/en/industry/2026/10/30/2026103009541164824)).

**Why it matters:** Actuators are a robot's joint muscles. Wheels push those motors through their full torque-speed range, while a learned (RL) whole-body controller keeps everything upright. Train in simulation, then land the move on real hardware the first time: that is Sim2Real working. And the muscles now have a supplier. Actuators make up about 60% of a humanoid's material cost ([Korea Herald](https://www.koreaherald.com/article/10651569)), so whoever makes them at scale sets the price of the body.

**My take:** Wheels, most of the time. Most of the world we'd put robots in is flat floor. I loved the spin jump, I'll admit it. But the real news is underneath: the muscles finally have a factory.

[Watch the 15-sec version](https://www.instagram.com/reel/DfsVMMoCNM2/)

## The thread: brains you license, bodies you build

Put the five on one stack and they sort themselves.

[IMAGE: diagram1-robot-stack.png]
*The robot stack, this week. The brain moves between places. The body doesn't.*

At the top, the brain. NVIDIA and Google both want to be the layer everyone else builds on. GR00T 2 lowers the cost of teaching. Gemini Robotics 2.5 is already shipped to partners, not consumers. It feels like Android in 2008: one brain, many phones.

In the middle, the body. Atlas on wheels is not a product, but the actuators under it are becoming a supply chain, with Hyundai Mobis making them.

At the bottom, the place. Ring and Amazon are betting on the home. Mercedes is testing the factory. The brain travels between places. The body doesn't.

**The brain is becoming something you license. The body is still something you bet on.**

## What I'm watching next week

- Whether anyone outside NVIDIA reproduces GR00T 2's one-demo numbers.
- Ring's Rover Cam preorders ahead of its December 16 ship date, and whether the Drone Cam clears the FCC.

---

The brain race is crowded now. The body race is where the bets are.

Factory first, or home first? Tell me your prediction :)

[PHOTO + lowercase italic caption — Soojin adds]

Unrelated, but … [SONG — Soojin adds]
