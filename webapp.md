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
    Welcome to the IPA computational toolkit. Most users can go straight to the core Data Analysis Platform. If you are starting with raw data formats, use our companion file formatting utilities below to prepare your datasets first.
  </p>


  <div style="background-color: #f0f4f8; border: 2px solid #b8daff; border-top: 6px solid #1b365d; border-radius: 8px; padding: 30px; margin-bottom: 40px; box-shadow: 0 4px 15px rgba(27, 54, 93, 0.08);">
    <span style="display: inline-block; background-color: #1b365d; color: #ffffff; font-size: 0.75em; font-weight: bold; padding: 4px 10px; border-radius: 3px; margin-bottom: 12px; text-transform: uppercase; letter-spacing: 0.05em;">Core Analysis Platform</span>
    
    <h2 style="color: #1b365d; margin-top: 0; margin-bottom: 12px; font-size: 1.7em;">Data Analysis Tool</h2>
    <p style="font-size: 1em; color: #2d3748; margin-bottom: 25px;">
      The primary evaluation environment. Upload your formatted coordinate matrices and target arrays to run rigid body transformations, calculate spatial residuals, and execute Robust Omnibus precision tests against baseline trends.
    </p>

    <a href="[Insert Live Data Analysis Tool URL Here]" target="_blank" style="display: inline-flex; align-items: center; background-color: #1b365d; color: #ffffff; padding: 14px 28px; font-size: 1.05em; font-weight: bold; text-decoration: none; border-radius: 4px; box-shadow: 0 3px 6px rgba(0,0,0,0.15); margin-bottom: 25px;">
      <svg style="width: 22px; height: 22px; margin-right: 10px; fill: #ffffff; flex-shrink: 0;" viewBox="0 0 24 24">
        <path d="M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/>
      </svg>
      Launch Data Analysis Platform
    </a>

    <div style="display: flex; gap: 20px; flex-wrap: wrap; border-top: 1px solid #d0e0f0; padding-top: 20px;">
      <div style="flex: 1; min-width: 240px;">
        <strong style="color: #1b365d; font-size: 0.9em; display: block; margin-bottom: 5px;">Platform Documentation:</strong>
        <a href="[Insert Analysis Manual PDF URL Here]" target="_blank" style="color: #1b365d; font-size: 0.9em; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center;">
          <svg style="width:16px; height:16px; margin-right:6px; fill:#1b365d;" viewBox="0 0 24 24"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"/></svg>
          Download Analysis User Manual (PDF)
        </a>
      </div>
      <div style="flex: 1; min-width: 240px;">
        <strong style="color: #1b365d; font-size: 0.9em; display: block; margin-bottom: 5px;">Validation Sample Data Bundle:</strong>
        <a href="[Insert Analysis Sample ZIP URL Here]" target="_blank" style="color: #1b365d; font-size: 0.9em; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center;">
          <svg style="width:16px; height:16px; margin-right:6px; fill:#1b365d;" viewBox="0 0 24 24"><path d="M10 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2h-8l-2-2z"/></svg>
          Download Reference Examples (.zip)
        </a>
        <span style="display: block; font-size: 0.8em; color: #555; margin-top: 4px; line-height: 1.4;">
          Includes nested tracking folders (Example 1 &amp; 2) capturing baseline and subsequent target timepoints.
        </span>
      </div>
    </div>
  </div>


  <div style="text-align: center; margin: 35px 0 25px 0;">
    <span style="background-color: #ffffff; padding: 0 15px; color: #718096; font-size: 0.9em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.05em;">File Preparation Utilities (Optional)</span>
    <hr style="border: 0; border-top: 1px solid #e2e8f0; margin-top: -10px; z-index: -1;">
  </div>


  <div style="display: flex; gap: 20px; flex-wrap: wrap;">

    <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e2e8f0; border-top: 4px solid #718096; padding: 20px; border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.02); display: flex; flex-direction: column; justify-content: space-between;">
      <div>
        <span style="display: inline-block; background-color: #edf2f7; color: #4a5568; font-size: 0.7em; font-weight: bold; padding: 2px 6px; border-radius: 3px; margin-bottom: 8px; text-transform: uppercase;">Optional Link 1</span>
        <h3 style="color: #2d3748; margin-top: 0; margin-bottom:
