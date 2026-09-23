---
standalone: true
title: Home
slug: home
projeto: ''
pageSettings:
  language: pt-BR
  link_pt_br: '#'
  link_en: '#'
  link_es: '#'
  animations: enable_all
  direction: left
  seoTitle: ''
  seoDescription: ''
  seoKeywords: []
  seoImage: ''
pageTheme:
  primaryColor: '#272725'
  secondaryColor: '#e5e9d3'
  highlightColor: '#dddcd0'
  auxiliaryColor: '#b096a1'
  displayFont: https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,200..800&display=swap
  textFont: ''
  spacingPatterns:
    - name: 10px
      mobile: 10px
      tablet: 10px
      desktop: 10px
pageInclude: null
modules:
  - type: MapBox
    style: mapbox://styles/comuni-dados/ck87kqz1v0hlt1iptdomrfl1y
    token: pk.eyJ1IjoiY29tdW5pLWRhZG9zIiwiYSI6ImNqdWxlaHRqbjIycjE0M3BpamY3a3c4aWUifQ.HGizp_QckKQVjAZnnw8qAg
    centerLng: '28.84322773404291'
    centerLat: '-2.504769573673098'
    zoom: '2'
    bearing: '0'
    pitch: '0'
    layers: ''
    columnAlign: left
    floatingText: false
    views:
      - id: view1
        centerLng: '28.873985743717075'
        centerLat: '-2.502155723319132'
        zoom: '16'
        mobileZoom: '16'
        duration: '2000'
        bearing: '0'
        pitch: '0'
        layers: |-
          "comuni-dados.72eyargqudus"
          comuni-dados.72eyargqudus
          brule
          "brule"
          test
          "test"
        title: ''
        notes: ''
        items: []
components:
  - type: Group
    id: main
    shortTitle: Bem Vindo
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/img-20260921-wa0057.jpg
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# BUKAVU BRÛLE'
        column2:
          components:
            - type: Spacer
              desktop: 130px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: À Bukavu, la nuit ne protège plus du feu. Pendant que la ville dort, les flammes gagnent des habitations, dévorent des souvenirs et transforment en quelques minutes le fruit de plusieurs années de labeur en un tas de tôles et de cendres. Chaque nouveau sinistre provoque l’émotion, la solidarité spontanée et quelques appels à l’aide. Puis le silence revient, jusqu’au prochain brasier.
            - type: Spacer
              desktop: 30px
              tablet: ''
              mobile: ''
      - type: Spacer
        desktop: 200px
        tablet: 200px
        mobile: 200px
  - type: Group
    id: intro
    shortTitle: Intro
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Column
        paddingTop: false
        paddingBottom: true
        components:
          - type: Text
            hasDropCap: false
            content: |-
              _Une investigation de auteur 1, auteur 2, auteur 3_

              **Bukavu, 21 septembre 2026**
          - type: Text
            hasDropCap: false
            content: 'À 23 h 43, dans la nuit, des flammes ont de nouveau embrasé des maisons vers Hebron-Nguba, dans la commune d’Ibanda. À Bukavu, l’incendie n’est plus un accident isolé : il devient une inquiétante habitude, avec son cortège de familles sinistrées, de biens réduits en cendres et de vies bouleversées.'
          - type: Pullquote
            content: Le feu est partie d'une maison où il y avait deuil, on ne sait pas ce qui s'est passé, directement nous avons tous été surpris par le feu. La priorité était de sauver d'abord les enfants. Le feu a été maîtrisé deux heures après avoir consumé deux avenues. J'ai aussi tout perdu,  je ne savais pas sauver les enfants et les biens à la fois
            txtColor: ''
            bgColor: ''
            byline: Milenge Pascal, responsable d'une famille victime
  - type: Map
    id: '01'
    shortTitle: '01'
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    bgColor: Secondary
    components:
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: view1
      - type: Spacer
        desktop: 30px
        tablet: ''
        mobile: ''
      - type: Text
        hasDropCap: false
        content: "###### Un nouvel incendie gigantesque s'est déclaré dans la ville de Bukavu, précisément aux avenues Irambo 1 et 2 au quartier Nyalukemba, la nuit de dimanche à ce lundi 21 septembre."
    columnAlign: left
    floatingText: true
---
