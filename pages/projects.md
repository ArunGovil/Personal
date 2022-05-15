---
title: Projects - Arun Govil
display: Projects
projects:
  Recent:
    - name: "DawkinsScale"
      link: "https://arungovil.github.io/DawkinsScale"
      desc: "Simple representation of Dawkins scale of faith."
      icon: "i-carbon-ruler"
    - name: "StepperForm"
      link: "https://github.com/ArunGovil/StepForm"
      desc: "Stepper form in ReactJs with Context API"
      icon: "i-carbon-chart-stepper"

  College:
    - name: "ShareNotes"
      link: "https://github.com/ArunGovil/ShareNotesApp"
      desc: "React Native note sharing app for college."
      icon: "i-carbon-share"
    - name: "NotesApp"
      link: "https://github.com/ArunGovil/NotesApp"
      desc: "Minimal note sharing app for classroom."
      icon: "i-carbon-book"
    - name: "BloodHub"
      link: "https://github.com/ArunGovil/BloodHubApp"
      desc: "Realtime blood donor android app for college."
      icon: "i-carbon-rain-drop"
    - name: "ProductPage"
      link: "https://github.com/ArunGovil/ProductPage"
      desc: "Simple product landing page using ReactJs."
      icon: "i-carbon-blog"
    - name: "Free Course Search"
      link: "https://github.com/ArunGovil/Free-Course"
      desc: "Free courses to learn during covid."
      icon: "i-carbon-course"
    - name: "College Webpage"
      link: "https://github.com/ArunGovil/CollegeWebsite"
      desc: "College website frontend using HTML, CSS & JS"
      icon: "i-carbon-html"
---

<ClientOnly>
  <Plum/>
</ClientOnly>

<ListProjects :projects="frontmatter.projects"/>
