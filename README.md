# Topical-EHR

An [open-source](https://github.com/topical-ehr/topical-ehr) prototype of an research-focused EHR

## Designed for research & innovation

* A test-bed for innovative ideas
* Open-Source means everything can be modified
* Primarily focused on end-user UX - can be made to work with existing FHIR-based systems
* Not for clinical use - can start fresh & break things

## Features

* **Topics** (e.g. Heart Disease) bring together a free-text summary with related diagnoses, prescriptions, tests, letters, etc - aiming to streamline complex histories and shared care
* **Timeline** column chronologically shows observations, test results & EMR changes
* **AI-assisted** summarisation and coding
* **Clinical Decision Support** helpers & alerts
* Other **UX** experiments - like auto-complete based prescription orders
* ...whatever **you** want to experiment with!

## Tech

* Web-application made using popular modern technologies (React, TypeScript)
* Plugin-based architecture for extensibility
* FHIR-based
    * comes with [CandleLite](https://github.com/topical-ehr/candlelite), a new lightweight FHIR server written from the ground-up in F#
    * can run entirely inside a web browser using sqlite for easy & cheap server-less deployments and isolation between users

# Interested?

Advice, support & collaboration would be most welcome: [https://www.linkedin.com/in/eugene-lubarsky-7076003/](https://www.linkedin.com/in/eugene-lubarsky-7076003/)

# Demo (🚧 work-in-progress)

Please use desktop Chrome or Firefox. Mobile devices are not currently supported.

[Link to demo](https://topicalehr-demo.vercel.app/patient/3)

## To try
* Double-click on "Heart disease" to edit the topic
* Start typing "atenolol" in the new order textbox and press enter when it comes up
* Click "Suggest conditions" to extract conditions from free-text (currently powered by GPT-3.5)

## Thanks to
* FHIR Terminology powered by the public instance of [CSIRO Ontoserver](https://ontoserver.csiro.au/)

# Screenshot


<img alt="screenshot" src="https://github.com/topical-ehr/website/assets/932521/9c536155-2f74-40ca-9d7d-3f075465bff5">

