"Jetsen Cybernetics I — House-Bots for Humans"
"Serge and the JAMMERS platform — warm, trustworthy companion robots and a three-helper AI model built for people, not paperclips."
---

# Jetsen Cybernetics
*Built with intention, not hype.*

**Why We’re Building House-Bots**

> If we’re going to build this future, we have to do it in the open, with clear rules and clear hearts.

AI and robots are arriving either way. The question isn’t “can we stop it?” — it’s “who do they serve, and how do we live with them?”

### The Worry
- “Robots will take our jobs.”
- “AI will flood the world with garbage.”
- “A few companies will own everything.”
- “Everything is moving too fast to be safe or fair.”

Those aren’t irrational fears. They’re signals. This project exists because we take them seriously.

### The Alternative
We want robots that live with us, not above us:

- trustworthy, warm, honest about what they are  
- doing real work in homes and cities  
- built with clear limits and accountability  

Not grey stormtrooper machines.  
Not ad billboards on wheels.  
Real helpers. House-bots. Companions with boundaries.

**Draft link:** [1st draft](the-worry.md)

---

## Platform
**JAMMERS — The Robotics Backbone**

JAMMERS is the engineering backbone that lets Serge-like bots exist: a modular, CUDA-powered robotics platform designed for home-scale embodied AI.

### Design Goals
- **Modular** — parts can be swapped, repaired, and upgraded.
- **Safe** — power and logic separated; failures fail safe, not dramatic.
- **Scalable** — from pet-scale companions to mid-sized helper droids.
- **Transparent** — documented architecture instead of mystery boxes.

### Core Architecture

**Compute**
- 3× NVIDIA Jetson Orin Nano modules
- C++ end-to-end, accelerated with CUDA
- Each module with a clear role:
  - **Coordinator** — speech, planning, connectivity
  - **Vision** — cameras, depth, spatial understanding
  - **Motion** — locomotion, balance, actions

**Power**
- Distributed LiFePO₄ battery system
- Separate rails for compute, motors, peripherals
- Designed to reduce electrical noise, spikes, and cascades

**Motion / Chassis**
- 20 cm ball-drive base with stabilization
- NEMA-class steppers + DM542 drivers
- Grasping arm/hand for simple manipulation tasks
- Mechanical design intentionally scalable to heavier frames later

### Safety & Fault Tolerance
- Each AI core runs on its own power + data domain.
- If one domain fails, others can shut down safely or load minimal models to **limp home**.

> No runaway behavior. No drama.  
> When things go wrong, the robot gets small, honest, and safe.

---

## Three Helpers
**Three Helpers, Not One Overlord**

Instead of a single godlike AI making decisions for everyone, we imagine three clear, bounded helpers that work for you.

### 1) The Cloud Helper
*Your paperwork brain.*

Lives online. Handles the boring admin: money, bills, taxes, calendars, bookings, documents.

It keeps your life organized on paper. It does not replace your judgment or your rights.

### 2) The House Helper
*Your domestic partner in metal.*

Lives in your home, in a body. Helps with cooking support, cleaning runs, basic repairs, kid-wrangling, tutoring, and small errands.

It learns how your household works and how you like things done, and behaves like a respectful, capable housemate who never sleeps.

### 3) The Work Helper
*Your apprentice, then your colleague.*

Goes with you into the world (physically or remotely). You teach it your job, step by step, with safety boundaries and oversight.

Once it can do meaningful chunks of the work, it takes on those tasks — and the wages go to you, the trainer and owner. Robots don’t erase your contribution; they multiply it.

### Why Three?
- **Fairness** — value flows back to people, not just the platforms.
- **Safety** — each helper has a clear role and clear limits.
- **Resilience** — if one fails or misbehaves, the others don’t domino with it.

Many small, bounded helpers are safer than one giant unchecked brain. That’s the philosophy behind Serge and the JAMMERS platform.

---

## About
**Who’s Building This?**

This is an applied robotics lab project: one engineer, a lifetime of systems thinking, and a stubborn refusal to leave the future of embodied AI hidden behind closed doors.

The goal is simple and difficult at the same time: build a trustworthy, lovable, technically serious house-bot platform the public can actually live with.

If embodied AI is coming into homes, it should be shaped by people who care about everyone.

---

© 2026 Jetsen Cybernetics — *Built with intention, not hype.*
