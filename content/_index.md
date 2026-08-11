---
title: NeuroConsult - Neuroscience-Based B2B Consulting
summary: "Professional B2B consulting, coaching, and lectures by neuroscientists and university professors to boost your company's productivity."
date: 2026-08-12
design:
  spacing: 6rem
type: landing
sections:
  - block: hero
    content:
        eyebrow: "Neuroscience & Productivity"
        title: "Unlock Your Company's Potential with NeuroConsult"
        text: "Led by a family of distinguished neuroscientists and university professors, we provide expert consulting, individual coaching, and transformative lectures aimed at enhancing organizational performance."
        primary_action:
          text: Get in Touch
          url: "#contact"
          icon: hero/arrow-right
          style: gradient
        secondary_action:
          text: Learn More
          url: "/#services"
          icon: hero/information-circle
          style: text
        trust:
          stars: 5
          text: Trusted by top universities and industry leaders
    design:
        layout: split-left
        size: tall
        alignment: left
        background:
          gradient:
            type: radial
            start: primary-500
            end: transparent
            position: "50% 20%"
            shape: ellipse
            size: "80% 80%"
        text_color_light: true
        css_class: relative overflow-hidden
        css_style: "min-height: 70vh;"
    id: intro
  - block: features
    content:
        title: Our Expertise
        text: Tailored services blending neuroscience and business strategy.
        items:
          - name: B2B Consulting
            description: Optimize your organizational processes with neuroscience insights.
            icon: hero/brain
          - name: Individual Coaching
            description: Personalized coaching to unlock leadership potential.
            icon: hero/user
          - name: "Lectures & Workshops"
            description: Engaging talks to inspire and educate your teams.
            icon: hero/academic-cap
    design:
        layout: grid
        background:
          color: primary-50
    id: services
  - block: cta-card
    content:
        title: "Ready to elevate your team’s performance?"
        text: Connect with NeuroConsult today and discover how neuroscience can transform your business.
        button:
          text: Contact Us
          url: "#contact"
          icon: hero/phone
          new_tab: false
    design:
        background:
          gradient:
            type: linear
            start: primary-500
            end: secondary-600
        text_color_light: true
    id: cta
  - block: testimonials
    content:
        title: What Our Partners Say
        text: Trusted by leaders across industries.
        items:
          - text: “NeuroConsult helped our executive team rethink leadership and improve productivity.”
            name: Dr. Elena Ivanova
            role: "CEO, BrainTech Inc."
            image: people/elena.jpg
          - text: “Their lectures bridge science and business with clarity and impact.”
            name: Prof. Michael Torres
            role: Harvard University
            image: people/michael.jpg
    design:
        background:
          color: primary-100
        section_break:
          fade_top: "#ffffff"
    id: testimonials
---

