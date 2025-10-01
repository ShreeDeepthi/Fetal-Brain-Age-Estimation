Fetal Brain Age Estimation using Deep Learning

Project: Fetal Brain Age Estimation using VGG16, ResNet50, Baseline CNN with Explainable AI (SHAP, LIME)

Overview

This repository implements deep learning models to estimate fetal brain age from ultrasound/MRI images (or other medical image modalities). It includes training and evaluation pipelines for:

VGG16 (transfer learning)

ResNet50 (transfer learning)

Baseline CNN (custom architecture trained from scratch)

Additionally, model interpretability techniques are integrated:

SHAP (Deep SHAP / GradientExplainer) for global and local explanations

LIME for local instance-level explanations

The aim is to provide accurate age prediction and clinically meaningful explanations to support model trust and diagnosis.
