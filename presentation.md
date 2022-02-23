<!-- .slide: data-background-color="var(--r-main-color)"  -->

# Resilience Against Downstream Failures

???

---

## Mario Fernandez

<h3 class="main">
Wayfair
</h2>
 
???

- I'm an engineer at Wayfair
- In case you don't know, Wayfair is an online retailer that sells furniture

---

<h2 class="main">
What I Want to Cover
</h2>

<h3 class="fragment fade-up">
Resilience Operators
</h3>

<h3 class="fragment fade-up">
Fallbacks
</h3>

<h3 class="fragment fade-up">
The Next Level
</h3>

???

---

<!-- .slide: data-background-color="var(--r-main-color)"  -->

# A Bit of Context

---

## Partner Home @ Wayfair

---

<!-- .slide: data-background-image="images/partner-home.png" data-background-size="auto 100%" -->

???

- This is Partner Home
- This is the portal that suppliers use in Wayfair to upload their wares, track inventory, logistics, and so on
- It's less visible than the store that most of our users experience. It's nevertheless really important for the health of the business
---

## Rough numbers

### ~100 flows
### ~30 experience teams

???

- It's a pretty significant piece of software, with a lot of teams involved

---

<!-- .slide: data-background-image="images/decoupling.png" data-background-size="90% auto" -->

???

- This application started, as it often does, as a monolith written in PHP. 
- Things have changed in the last two years, and we're moving to an architecture based on decoupled services

---

<!-- .slide: data-background-image="images/navigation.png" data-background-size="100% auto" -->

???

- let's say, a navigation bar
- it's present in almost every page
- in a decoupled application architecture, you have to make sure that every individual app renders it

---

<!-- .slide: data-background-color="var(--r-main-color)"  -->

# Facing Issues

---

<!-- .slide: data-background-image="images/errors.png" data-background-size="auto 90%" -->

---

<!-- .slide: data-background-image="images/incidents.png" data-background-size="auto 90%" -->

---

## Humane On-Call
### DevoxxUK 2021
### www.youtube.com/watch?v=X59Sfaey5N4

---

<!-- .slide: data-background-color="var(--r-main-color)"  -->

# Resilience

---

