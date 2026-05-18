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
    Recognizing the significant computational burden of processing spatial coordination metrics, this free web utility streamlines data processing for the Terrestrial Laser Scanner (TLS) Interim Performance Assessment (IPA) protocol. Users can seamlessly upload target center coordinates extracted from their scanner's software along with field-recorded tape measurements to automate compliance calculations[cite: 518, 520, 634].
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

  <hr style="border: 0; border-top: 1px solid #eaeaea; margin: 30px 0;">

  <h3 style="color: #1b365d; margin-bottom: 15px;">Automated Processing Functions</h3>
  <p>The backend of the application performs the data reductions defined by the draft forensic standard[cite: 344]:</p>
  
  <ul style="padding-left: 20px; list-style-type: square; margin-bottom: 20px;">
    <li style="margin-bottom: 10px;">
      <strong style="color: #1b365d;">Bundle Adjustment Alignment:</strong> Converts independent target datasets into a centralized frame of reference using a rigid body transformation minimizing coordinate translation and rotation discrepancies[cite: 142, 143].
    </li>
    <li style="margin-bottom: 10px;">
      <strong style="color: #1b365d;">Residual Calculation:</strong> Automatically maps Cartesian values to spherical coordinate frames ($\theta, \phi, r$) and calculates spherical residuals relative to composite averages[cite: 91, 93, 150].
    </li>
    <li style="margin-bottom: 10px;">
      <strong style="color: #1b365d;">Robust Omnibus Hypothesis Testing:</strong> Executes a multivariate analog to Levene's test to statistically evaluate ($H_0: \Sigma_1 = \Sigma_2$) whether your instrument's baseline operational precision has shifted significantly over longitudinal testing windows[cite: 134, 156, 157].
    </li>
    <li style="margin-bottom: 10px;">
      <strong style="color: #1b365d;">Data Ellipse Visualization:</strong> Generates interactive bivariate scatterplots bounded by proportional variance and covariance ellipses, allowing users to quickly see exactly how an instrument's precision profile may be tracking over time[cite: 182, 189, 190].
    </li>
  </ul>

  <div style="margin-top: 50px; border-top: 1px solid #eaeaea; padding-top: 25px; text-align: center;">
    <a href="{{ '/' | relative_url }}" style="display: inline-flex; align-items: center; background-color: #1b365d; color: #ffffff; padding: 10px 20px; font-size: 0.95em; font-weight: bold; text-decoration: none; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
      <svg style="width: 18px; height: 18px; margin-right: 8px; fill: #ffffff; flex-shrink: 0;" viewBox="0 0 24 24">
        <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/>
      </svg>
      Back to Home Page
    </a>
  </div>

</div>
