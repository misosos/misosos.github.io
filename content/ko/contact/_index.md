---
title: Contact
summary: ''
type: landing

#cascade:
#  - target:
#      path: '{/contact/*/**}'
#    type: docs
#    params:
#      show_breadcrumb: true

sections:
  - block: features
    id: contact
    content:
      title: Contact
      items:
        - icon: hero/envelope
          name: Email
          description: '[miso0307@jbnu.ac.kr](mailto:miso0307@jbnu.ac.kr)'
          css_class: "flex flex-row items-center gap-3"
        - icon: hero/phone
          name: Phone
          description: '010-5596-7294'
          css_class: "flex flex-row items-center gap-3"
        - icon: hero/map
          name: Address
          description: '54896 전북특별자치도 전주시 덕진구 백제대로 567 전북대학교 공과대학 7호관'
          css_class: "flex flex-row items-center gap-3"
    design:
      columns: 3
      css_class: "text-center"
      spacing:
        padding: ["0", "0", "0", "0"]     

  - block: markdown
    content:
      title: 찾아오시는 길
      text: |-
        <iframe width="425" height="350" src="https://www.openstreetmap.org/export/embed.html?bbox=127.1344496,35.8460132,127.1344496,35.8460132&layer=mapnik&marker=35.8460132,127.1344496"></iframe>
    spacing:
      padding: ["0", "0", "0", "0"]   
---