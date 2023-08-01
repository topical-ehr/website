# Topical-EHR

A research-focused [open-source](https://github.com/topical-ehr/topical-ehr) EHR prototype

## For research & innovation

* A test-bed for innovative ideas & emerging technologies - open-source means all parts of the system can be freely modified
* Not for clinical use - can start fresh & break things

## Aims

* Help multidisciplinary teams provide high-quality holistic care
* A focus on design & UX - it should be pleasant, efficient & easy to use


## Features under development

* **Topics** (e.g. Heart Disease) bring together a free-text summary with related diagnoses, prescriptions, tests, letters, etc - aiming to streamline complex histories and shared care
* **Timeline** column chronologically shows observations, test results & EMR changes
* **AI-assisted** summarisation & coding
* **Clinical Decision Support** helpers & alerts
* Other **UX** experiments - like auto-complete based prescription orders
* ...whatever **you** want to experiment with!

## Tech

* Web-application made using popular modern technologies (React, TypeScript)
* Architecture aims for easy customisation & extensibility
* Should be comfortable to build & develop on most laptops
* [FHIR](https://www.hl7.org/fhir/)-based
    * comes with [CandleLite](https://github.com/topical-ehr/candlelite), a new lightweight FHIR server written from the ground-up in [F#](https://fsharp.org/)
    * can run entirely inside a web browser for easy & cheap server-less deployments and isolation between users
    * could be made to "plug in" to existing systems

# Interested?

Advice, support & collaboration would be most welcome: [https://www.linkedin.com/in/eugene-lubarsky-7076003/](https://www.linkedin.com/in/eugene-lubarsky-7076003/)

# Demo (🚧 work-in-progress 🚧)

Please use desktop Chrome or Firefox. Mobile devices are not currently supported.

[Link to demo](https://topicalehr-demo.vercel.app/patient/3)

## To try
* Double-click on "Heart disease" to edit the topic
* Start typing "atenolol" in the new order textbox and press enter when it comes up
* Click "Suggest conditions" to extract conditions from free-text (currently powered by GPT-3.5)

## Thanks to
* FHIR Terminology powered by the public instance of [CSIRO Ontoserver](https://ontoserver.csiro.au/)
* Synthetic data courtesy of [Synthea](https://synthetichealth.github.io/synthea/)

# Screenshot


<img alt="screenshot" src="https://github.com/topical-ehr/website/assets/932521/9c536155-2f74-40ca-9d7d-3f075465bff5">

