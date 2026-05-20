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

  <h1 style="color: #1b365d; margin-top: 0; margin-bottom: 15px; font-size: 2.2em;">TLS Web Application Suite</h1>
  
  <p style="margin-bottom: 35px; color: #555;">
    The Interim Performance Assessment (IPA) computational toolkit provides specialized utilities for automated data processing, structural reduction, and forensic standard compliance validations.
  </p>


  <div style="background-color: #ffffff; border: 1px solid #e2e8f0; border-top: 4px solid #718096; border-radius: 6px; padding: 25px; margin-bottom: 40px; box-shadow: 0 2px 5px rgba(0,0,0,0.02);">
    <span style="display: inline-block; background-color: #edf2f7; color: #4a5568; font-size: 0.75em; font-weight: bold; padding: 3px 8px; border-radius: 3px; margin-bottom: 10px; text-transform: uppercase; letter-spacing: 0.05em;">Step 1: Preparation Utility</span>
    <h2 style="color: #2d3748; margin-top: 0; margin-bottom: 12px; font-size: 1.5em;">1. Data Processing Tool</h2>
    <p style="font-size: 0.95em; color: #555; margin-bottom: 20px;">
      A "one-and-done" utility application used to convert independent raw coordinate logs into the uniform structural matrix format required by the main evaluation platform. Run this tool once whenever you generate an entirely new field dataset.
    </p>

    <a href="[Insert Live Data Processing Tool URL]" target="_blank" style="display: inline-flex; align-items: center; background-color: #4a5568; color: #ffffff; padding: 10px 18px; font-size: 0.95em; font-weight: bold; text-decoration: none; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); margin-bottom: 20px;">
      Launch Data Processing Tool &rarr;
    </a>

    <div style="display: flex; gap: 20px; flex-wrap: wrap; border-top: 1px solid #edf2f7; padding-top: 15px;">
      <div style="flex: 1; min-width: 240px;">
        <strong style="color: #4a5568; font-size: 0.9em; display: block; margin-bottom: 5px;">Documentation</strong>
        <a href="[Insert Processing Manual PDF URL]" target="_blank" style="color: #1b365d; font-size: 0.9em; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center;">
          <svg style="width:16px; height:16px; margin-right:5px; fill:#1b365d;" viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-5 14H7v-2h7v2zm3-4H7v-2h10v2zm0-4H7V7h10v2z"/></svg>
          Download Processing Manual (PDF)
        </a>
      </div>
      <div style="flex: 1; min-width: 240px;">
        <strong style="color: #4a5568; font-size: 0.9em; display: block; margin-bottom: 5px;">Data Validation Pack</strong>
        <a href="[Insert Processing Sample ZIP URL]" target="_blank" style="color: #1b365d; font-size: 0.9em; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center;">
          <svg style="width:16px; height:16px; margin-right:5px; fill:#1b365d;" viewBox="0 0 24 24"><path d="M19.35 10.04C18.67 6.59 15.64 4 12 4 9.11 4 6.6 5.64 5.35 8.04 2.34 8.36 0 10.91 0 14c0 3.31 2.69 6 6 6h13c2.76 0 5-2.24 5-5 0-2.64-2.05-4.78-4.65-4.96zM17 13l-5 5-5-5h3V9h4v4h3z"/></svg>
          Download Example Files (.zip)
        </a>
        <span style="display: block; font-size: 0.8em; color: #718096; margin-top: 4px; line-height: 1.4;">
          Contains 1 sample dataset supplied in both **CSV** and **TXT** formats.
        </span>
      </div>
    </div>
  </div>


  <div style="background-color: #f0f4f8; border: 1px solid #d0e0f0; border-top: 4px solid #1b365d; border-radius: 6px; padding: 25px; margin-bottom: 40px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">
    <span style="display: inline-block; background-color: #1b365d; color: #ffffff; font-size: 0.75em; font-weight: bold; padding: 3px 8px; border-radius: 3px; margin-bottom: 10px; text-transform: uppercase; letter-spacing: 0.05em;">Step 2: Core Platform</span>
    <h2 style="color: #1b365d; margin-top: 0; margin-bottom: 12px; font-size: 1.5em;">2. Data Analysis Tool</h2>
    <p style="font-size: 0.95em; color: #333; margin-bottom: 20px;">
      The primary evaluation dashboard. Upload your processed coordinate metrics and target arrays to resolve rigid body transformations, run Robust Omnibus precision tests, and monitor variations against system specifications. 
    </p>

    <a href="[Insert Live Data Analysis Tool URL Here]" target="_blank" style="display: inline-flex; align-items: center; background-color: #1b365d; color: #ffffff; padding: 12px 24px; font-size: 1em; font-weight: bold; text-decoration: none; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.15); margin-bottom: 25px;">
      <svg style="width: 20px; height: 20px; margin-right: 8px; fill: #ffffff; flex-shrink: 0;" viewBox="0 0 24 24">
        <path d="M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/>
      </svg>
      Launch Data Analysis Platform
    </a>

    <div style="display: flex; gap: 20px; flex-wrap: wrap; border-top: 1px solid #d0e0f0; padding-top: 25px;">
      
      <div style="flex: 1; min-width: 240px;">
        <strong style="color: #1b365d; font-size: 0.95em; display: block; margin-bottom: 5px;">Platform Documentation</strong>
        <a href="[Insert Analysis Manual PDF URL Here]" target="_blank" style="color: #1b365d; font-size: 0.9em; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; margin-bottom: 10px;">
          <svg style="width:16px; height:16px; margin-right:5px; fill:#1b365d;" viewBox="0 0 24 24"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"/></svg>
          Download Analysis User Manual (PDF)
        </a>
      </div>

      <div style="flex: 1; min-width: 240px;">
        <strong style="color: #1b365d; font-size: 0.95em; display: block; margin-bottom: 5px;">Reference Data Library</strong>
        <a href="[Insert Analysis Sample ZIP URL Here]" target="_blank" style="color: #1b365d; font-size: 0.9em; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center;">
          <svg style="width:16px; height:16px; margin-right:5px; fill:#1b365d;" viewBox="0 0 24 24"><path d="M10 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2h-8l-2-2z"/></svg>
          Download Reference Data Bundle (.zip)
        </a>
        
        <div style="margin-top: 10px; font-size: 0.8em; color: #4a5568; line-height: 1.5; background-color: #ffffff; padding: 10px; border-radius: 4px; border: 1px solid #d0e0f0;">
          <strong>Included Tracking Folders:</strong>
          <ul style="margin: 4px 0 0 0; padding-left: 15px;">
            <li><strong>Example 1:</strong> Contains 2 subsequent arrays tracking instrument metrics over distinct testing windows.</li>
            <li><strong>Example 2:</strong> Contains 2 subsequent arrays mapping longitudinal shift deviations.</li>
          </ul>
        </div>
      </div>

    </div>
  </div>


  <div style="border: 2px dashed #cbd5e0; background-color: #fafbfe; border-radius: 6px; padding: 25px; margin-bottom: 30px; text-align: center;">
    <span style="display: inline-block; background-color: #e2e8f0; color: #718096; font-size: 0.7em; font-weight: bold; padding: 3px 8px; border-radius: 3px; margin-bottom: 10px; text-transform: uppercase; letter-spacing: 0.05em;">Upcoming Extension</span>
    <h3 style="color: #a0aec0; margin-top: 0; margin-bottom: 8px; font-size: 1.3em;">3. [Future Application Tool Name]</h3>
    <p style="font-size: 0.9em; color: #94a3b8; max-width: 600px; margin: 0 auto;">
      Additional diagnostic software modules and companion standard implementation utilities are currently under development and will be integrated here upon validation.
    </p>
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
