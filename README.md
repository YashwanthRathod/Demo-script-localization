# Demo-script-localization

## Problem Statement:
Given a demo script document, generate its localized version. The localized version is expected to satisfy following objectives:
1. Translate the language of the demo script to the language specified by the user.
2. Use names from the country specified by the user in the demo script.

## Guidelines for Localization
1. While using names of people from a country, please ensure that the same names are localized correctly for all their occurrences. For instance, if Alex Smith is to be changed to Rahul Sharma (considering the user has chosen the country to be India), then all occurrences of Alex and Alex Smith must be replaced with Rahul and Rahul Sharma in the document.
2. The input will be a demo script DOCX file and the output will be a localized demo script DOCX file.

## Expectations
1. Develop a pipeline, of your choice (no-LLM vs LLM), for generating a localized version of demo script. The pipeline will be used to generate localized scripts for documents (DOCX files) of varying lengths.
2. Additionally, wrap the pipeline behind a UI (Streamlit/Gradio) app, that allows one to upload the document and specify the language, and country, to generate the localized demo script and export it to a DOCX format.
3. Suggest strategies to evaluate the pipeline for correctness and quality of the localization. Be creative, we expect you to think about what kind of metric would be a close leading indicator of the correctness and quality of localized demo script. Where quality is subjective to our use-case of localizing demo scripts.
4. A thorough error analysis of the data and pipeline, along with points on how you would go about improving the model further is expected.
