---
layout: default
title: Web Application Tool
permalink: /webapp.html
---

<div style="max-width: 800px; margin: 0 auto; padding: 20px 10px; line-height: 1.7; color: #333;">

  <div style="background-color: #f9f9f9; border-left: 4px solid #1b365d; padding: 12px 20px; margin-bottom: 35px; border-radius: 4px; display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 15px;">
    <strong style="color: #1b365d; font-size: 1em;">Portal Navigation:</strong>
    <div style="display: flex; gap: 20px; flex-wrap: wrap;">
      <a href="{{ '/' | relative_url }}" style="color: #1b365d; text-decoration: none; font-weight: bold; font-size: 0.9em;">&larr; Home</a>
      <span style="color: #ccc; font-size: 0.9em;">|</span>
      <a href="{{ '/about.html' | relative_url }}" style="color: #1b365d; text-decoration: none; font-weight: bold; font-size: 0.9em;">About Project</a>
      <span style="color: #ccc; font-size: 0.9em;">|</span>
      <a href="{{ '/tutorials.html' | relative_url }}" style="color: #1b365d; text-decoration: none; font-weight: bold; font-size: 0.9em;">Tutorial Videos</a>
    </div>
  </div>

  <h1 style="color: #1b365d; margin-top: 0; margin-bottom: 15px; font-size: 2.2em;">TLS Web Application Tool</h1>
  
  <p>
    Recognizing the significant computational burden of processing spatial coordination metrics, this free web utility streamlines data processing for the Terrestrial Laser Scanner (TLS) Interim Performance Assessment (IPA) protocol. Users can seamlessly upload target center coordinates extracted from their scanner's software along with field-recorded tape measurements to automate compliance calculations.
  </p>

  <div style="background-color: #f0f4f8; border: 1px solid #d0e0f0; border-radius: 6px; padding: 25px; margin: 30px 0; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">
    <h4 style="color: #1b365d; margin-top: 0; margin-bottom: 10px; font-size: 1.2em;">Access the Computational App</h4>
    <p style="font-size: 0.95em; color: #555; margin-bottom: 20px;">
      Launch the external TLS analysis portal to compute distance errors, evaluate equality of covariance matrices, and model target uncertainty profiles.
    </p>
    <a href="[Insert Live Web App URL Here]" target="_blank" style="display: inline-flex; align-items: center; background-color: #1b365d; color: #ffffff; padding: 12px 24px; font-size: 1em; font-weight: bold; text-decoration: none; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.15);">
      <svg style="width: 20px; height: 20px; margin-right: 8px; fill: #ffffff; flex-shrink: 0;" viewBox="0 0 24 24">
        <path d="M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/>
      </svg>
      Launch TLS Analysis Application
    </a>
  </div>

  <div style="background-color: #ffffff; border: 1px solid #eaeaea; border-left: 4px solid #1b365d; border-radius: 4px; padding: 20px; margin-bottom: 30px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">
    <h4 style="color: #1b365d; margin-top: 0; margin-bottom: 8px; font-size: 1.1em;">Data Re-Formatting Tool</h4>
    <p style="font-size: 0.95em; color: #555; margin-bottom: 15px;">
      Need to prepare your raw coordinate logs? Use this utility script to instantly convert manufacturer software output formats into the exact CSV structure required by the main web application.
    </p>
    <a href="[Insert Pre-processing Tool Link Here]" target="_blank" style="color: #1b365d; font-weight: bold; text-decoration: none; font-size: 0.95em; display: inline-flex; align-items: center;">
      Format Data for Web App &rarr;
    </a>
  </div>

  <div style="display: flex; gap: 20px; flex-wrap: wrap; margin-top: 30px;">
    
    <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #eaeaea; padding: 20px; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">
      <h4 style="color: #1b365d; margin-top: 0; margin-bottom: 8px; font-size: 1.1em;">User Documentation Manual</h4>
      <p style="font-size: 0.9em; color: #666; margin-bottom: 15px;">
        Download the step-by-step PDF software guide detailing input data configurations, test execution requirements, and result log interpretation metrics.
      </p>
      <a href="[Insert User Manual Download Link Here]" target="_blank" style="color: #1b365d; font-weight: bold; text-decoration: none; font-size: 0.9em; display: inline-flex; align-items: center;">
        <svg style="width: 16px; height: 16px; margin-right: 6px; fill: #1b365d;" viewBox="0 0 24 24"><path d="M19.35 10.04C18.67 6.59 15.64 4 12 4 9.11 4 6.6 5.64 5.35 8.04 2.34 8.36 0 10.91 0 14c0 3.31 2.69 6 6 6h13c2.76 0 5-2.24 5-5 0-2.64-2.05-4.78-4.65-4.96zM17 13l-5 5-5-5h3V9h4v4h3z"/></svg>
        Download Documentation Manual
      </a>
    </div>

    <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #eaeaea; padding: 20px; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">
      <h4 style="color: #1b365d; margin-top: 0; margin-bottom: 8px; font-size: 1.1em;">Example Reference Datasets</h4>
      <p style="font-size: 0.9em; color: #666; margin-bottom: 15px;">
        Download verified sample target data vectors to run a test simulation and observe how the statistical assessment framework processes baseline metrics.
      </p>
      <a href="[Insert Example Data Download Link Here]" target="_blank" style="color: #1b365d; font-weight: bold; text-decoration: none; font-size: 0.9em; display: inline-flex; align-items: center;">
        <svg style="width: 16px; height: 16px; margin-right: 6px; fill: #1b365d;" viewBox="0 0 24 24"><path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/></svg>
        Download Sample Data (.zip)
      </a>
    </div>

  </div>

  <div style="margin-top: 50px; border-top: 1px solid #eaeaea; padding-top: 25px; text-align: center;">
    <a href="{{ '/' | relative_url }}" style="display: inline-flex; align-items: center; background-color: #1b365d; color: #ffffff; padding: 10px 20px; font-size: 0.95em; font-weight: bold; text-decoration: none; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
      <svg style="width: 18px; height: 18px; margin-right: 8px; fill: #ffffff; flex-shrink: 0;" viewBox="0 0 24 24">
        <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/>
      </svg>
      Back to Home Page
    </a>
  </div>

</div>
