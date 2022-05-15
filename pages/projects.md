---
title: Projects - Arun Govil
display: Projects
projects:
  # Recent:
  #   - name: 'Zeitreise'
  #     link: 'https://twitter.com/antfu7/status/1504639906232307712'
  #     desc: 'Time traveling for the Web'
  #     icon: 'i-mdi-clock-fast'
  #   - name: 'reTypewriter'
  #     link: 'https://twitter.com/antfu7/status/1505236765447458817'
  #     desc: 'Smartly reply the steps of your changes at ease.'
  #     icon: 'i-carbon-keyboard'

  College:
    - name: 'ShareNotes'
      link: 'https://github.com/ArunGovil/ShareNotesApp'
      desc: 'React Native note sharing app for college.'
      icon: 'i-carbon-share'
    - name: 'NotesApp'
      link: 'https://github.com/ArunGovil/NotesApp'
      desc: 'Minimal note sharing app for classroom.'
      icon: 'i-carbon-book'
    - name: 'BloodHub'
      link: 'https://github.com/ArunGovil/BloodHubApp'
      desc: 'Realtime blood donor android app for college.'
      icon: 'i-carbon-rain-drop'
    - name: 'ProductPage'
      link: 'https://github.com/ArunGovil/ProductPage'
      desc: 'Simple product landing page using ReactJs.'
      icon: 'i-carbon-blog'
    - name: 'Free Course Search'
      link: 'https://github.com/ArunGovil/Free-Course'
      desc: 'Free courses to learn during covid.'
      icon: 'i-carbon-course'
    - name: 'College Webpage'
      link: 'https://github.com/ArunGovil/CollegeWebsite'
      desc: 'College website frontend using HTML, CSS & JS'
      icon: 'i-carbon-html'

---

<ClientOnly>
  <Plum/>
</ClientOnly>

<ListProjects :projects="frontmatter.projects"/>
