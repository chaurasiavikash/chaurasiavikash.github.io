---
layout: page
permalink: /projects/
title: projects
description: Selected open-source software and computational projects.
nav: true
nav_order: 3
---

These projects collect open-source work in medical imaging, environmental modeling, machine learning, biomechanics, and accessibility tools. Each repository includes implementation details, usage notes, and project-specific documentation.

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(270px, 1fr)); gap: 1rem; margin-top: 1.25rem;">
  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Medical imaging and biomechanics</div>
      <h3 style="margin: 0.15rem 0 0;">BODIESReg: Registration of 3D human scans</h3>
    </div>
    <p style="margin: 0;">Open-source pipeline for registering 3D human scans to SMPL-family body models using pose-aligned initialization and geometric optimization.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Combines projection-based keypoint detection, inverse kinematics, and surface fitting.</li>
      <li>Supports automatic registration, manual correction, batch processing, visualization, and body measurements.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">OpenCV</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">ITK</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">SMPL</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/BODIESReg" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Marine ecosystem modeling</div>
      <h3 style="margin: 0.15rem 0 0;">Marine Ecosystem ML Surrogate Models</h3>
    </div>
    <p style="margin: 0;">Machine-learning surrogate models for an enhanced NPZD ecosystem model, designed to approximate marine biogeochemical dynamics more efficiently.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Compares Random Forest and PyTorch neural-network surrogates for nutrients, plankton, detritus, and chlorophyll.</li>
      <li>Uses synthetic North Atlantic training data and reports predictive performance up to R^2 = 0.906.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">PyTorch</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Scikit-learn</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Jupyter</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/AIMEC-NPZ" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Satellite methane monitoring</div>
      <h3 style="margin: 0.15rem 0 0;">TROPOMI Methane Emissions Monitoring</h3>
    </div>
    <p style="margin: 0;">End-to-end pipeline for methane hotspot detection and analysis using TROPOMI/Sentinel-5P data through Google Earth Engine.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Uses statistical anomaly detection and spatial clustering to identify emission sources.</li>
      <li>Includes Streamlit dashboard support for maps, time series, hotspot details, and data export.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Google Earth Engine</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Streamlit</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/spatial_mapping" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Satellite methane monitoring</div>
      <h3 style="margin: 0.15rem 0 0;">Super-Emitter Tracking System</h3>
    </div>
    <p style="margin: 0;">Framework for detecting, tracking, and analyzing methane super-emitters from TROPOMI satellite observations.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Combines multi-algorithm detection, temporal persistence filtering, and uncertainty-aware tracking.</li>
      <li>Implements trend analysis, change-point detection, lifecycle monitoring, and notification prioritization.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Statistical analysis</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">TROPOMI</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/super_emitter_tracking" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Soil carbon measurement</div>
      <h3 style="margin: 0.15rem 0 0;">High-Frequency Soil CO2 Simulation</h3>
    </div>
    <p style="margin: 0;">Computational framework for simulating automated soil CO2 chamber measurements and analyzing sampling-frequency effects.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Models environmental drivers, chamber physics, sensor behavior, flux calculation, and quality control.</li>
      <li>Detects Birch pulse events and quantifies 67-76% information loss under sparse sampling protocols.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Physics-based modeling</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Time series</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/terrapulse_simulation" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Peatland carbon dynamics</div>
      <h3 style="margin: 0.15rem 0 0;">Peatland Carbon Dynamics Framework</h3>
    </div>
    <p style="margin: 0;">Modeling framework for simulating peatland carbon balance under climate and management scenarios.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Represents sequestration, Q10-driven decomposition, management state, temperature, and precipitation effects.</li>
      <li>Provides command-line batch runs and Streamlit dashboard views for scenario analysis and export.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Biogeochemical modeling</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Streamlit</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/detection_algorithm" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Biomechanics documentation AI</div>
      <h3 style="margin: 0.15rem 0 0;">OpenSim RAG Chat Assistant</h3>
    </div>
    <p style="margin: 0;">Retrieval-augmented chat assistant for OpenSim biomechanics documentation using an open-source Mistral model.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Combines documentation retrieval, semantic search, vector storage, and context-aware answer generation.</li>
      <li>Includes model-loading and memory-management utilities for local open-source inference.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">FastAPI</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Hugging Face</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Vector databases</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/opensim-rag-mistral" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem; display: flex; flex-direction: column; gap: 0.65rem;">
    <div>
      <div style="font-size: 0.85rem; color: var(--global-theme-color); font-weight: 600;">Accessibility and computer vision</div>
      <h3 style="margin: 0.15rem 0 0;">Visual Assistant for Accessibility</h3>
    </div>
    <p style="margin: 0;">Locally hosted visual assistant for image description, OCR, and question answering about visual content.</p>
    <ul style="padding-left: 1.2rem; margin: 0;">
      <li>Integrates image description, text extraction, question answering, and text-to-speech.</li>
      <li>Runs through an accessible web interface with local processing and no external API requirement.</li>
    </ul>
    <div style="display: flex; flex-wrap: wrap; gap: 0.35rem; margin-top: auto;">
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Python</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">Computer vision</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">OCR</span>
      <span style="border: 1px solid var(--global-divider-color); border-radius: 999px; padding: 0.1rem 0.5rem; font-size: 0.8rem;">FastAPI</span>
    </div>
    <p style="margin: 0;"><a href="https://github.com/chaurasiavikash/visual_assistant" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>
</div>
