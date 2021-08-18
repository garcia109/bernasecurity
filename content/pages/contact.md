---
title: Contáctame
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |+
      Para ponerse en contacto por favor complete el siguiente formulario.

    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nombre
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: Correo
        label: Correo
        default_value: Tu correo electrónico
        is_required: true
      - input_type: select
        name: Motivo
        label: Motivo
        default_value: Por favor seleccione
        options:
          - Error en el sitio
          - Patrocinio
          - Otro
      - input_type: textarea
        name: Mensaje
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consentimiento
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que puedan ser contactados.
    submit_label: Enviar mensaje
seo:
  title: Contáctame
  description: Para ponerse en contacto por favor complete el siguiente formulario.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contáctame
      keyName: property
    - name: 'og:description'
      value: Para ponerse en contacto por favor complete el siguiente formulario.
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contáctame
    - name: 'twitter:description'
      value: Para ponerse en contacto por favor complete el siguiente formulario.
    - name: 'og:image'
      value: >-
        /images/logotipo-del-vector-de-seguridad-cibernética-con-marca-protección-y-verificación-concepto-escudo-internet-ilustración-195108388.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:image'
      value: >-
        /images/logotipo-del-vector-de-seguridad-cibernética-con-marca-protección-y-verificación-concepto-escudo-internet-ilustración-195108388.jpg
      keyName: property
      relativeUrl: true
layout: advanced
---
