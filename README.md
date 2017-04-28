
<!DOCTYPE html>
<html>

  <head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Jekyll Resume Template</title>

  <!-- Google font typography settings - defined in _config.yml -->
  
  <link href='https://fonts.googleapis.com/css?family=Lora:400,700|Open+Sans:400,300,800,700' rel='stylesheet' type='text/css'>
  

  <meta name="description" content="A resume template for Jekyll and GitHub Pages sites.">

  <link rel="stylesheet" href="css/main.css">
  <link rel="canonical" href="http://resume-template.joelglovier.com/">
  <link rel="icon" type="image/x-icon" href="/favicon.png" />
</head>


  <body class="theme-default">

    <div class="wrapper" itemscope itemtype="http://schema.org/Person">

      <header class="page-header">

        <!-- You can turn off the avatar in _config.yml by setting to false -->
        
        <img src="images/avatar.jpg" alt="my photo" class="avatar no-print" itemprop="image">
        

        <!-- Your name is defined in the _config.yml file -->
        <h1 class="header-name" itemprop="name">Homer J. Simpson</h1>

        <!-- Contact buttons don't work in print, configure in the _config.yml file, remove "print-only" to display always. -->
        <div class="header-contact-info print-only" itemprop="contact-info">
          <p>742 Evergreen Terrace, Springfield | 555-7334 | homerjsimpson@youremailaddress.com</p>
        </div>

        <div class="title-bar no-print">

          <!-- Your title is also defined in the _config.yml file -->
          <h2 class="header-title" itemprop="jobTitle">Nuclear Safety Inspector</h2>

          <!-- This is the markup for the icon links; moved out to an include because it's very verbose, and you shouldn't ever need to edit the markup (unless you want to re-order the icons); if you want to customize which links appear, define them in the _config.yml file -->
          <!-- and guess where these are defined? Yup, you guessed it: the _config.yml file -->

<ul class="icon-links">

  <!-- GitHub link -->
  
  <li class="icon-link-item"><a href="https://github.com/jglovier/resume-template" class="icon-link" itemprop="url"><svg class="icon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
   viewBox="0 0 28 28" enable-background="new 0 0 28 28" xml:space="preserve" width="28">
<path id="GitHub" fill-rule="evenodd" clip-rule="evenodd" fill="#D1CECC" d="M14.01,0C6.27,0-0.01,6.28-0.01,14.02
  c0,6.19,4.02,11.45,9.59,13.3c0.7,0.13,0.96-0.3,0.96-0.68c0-0.33-0.01-1.21-0.02-2.38c-3.9,0.85-4.72-1.88-4.72-1.88
  c-0.64-1.62-1.56-2.05-1.56-2.05c-1.27-0.87,0.1-0.85,0.1-0.85c1.41,0.1,2.15,1.44,2.15,1.44c1.25,2.14,3.28,1.52,4.08,1.16
  c0.13-0.91,0.49-1.52,0.89-1.87c-3.11-0.35-6.38-1.56-6.38-6.93c0-1.53,0.55-2.78,1.44-3.76C6.37,9.17,5.89,7.74,6.65,5.81
  c0,0,1.18-0.38,3.85,1.44c1.12-0.31,2.32-0.47,3.51-0.47c1.19,0.01,2.39,0.16,3.51,0.47c2.68-1.81,3.85-1.44,3.85-1.44
  c0.76,1.93,0.28,3.35,0.14,3.71c0.9,0.98,1.44,2.23,1.44,3.76c0,5.38-3.28,6.57-6.4,6.92c0.5,0.43,0.95,1.29,0.95,2.6
  c0,1.87-0.02,3.39-0.02,3.84c0,0.37,0.25,0.81,0.96,0.67c5.56-1.86,9.58-7.11,9.58-13.3C28.03,6.28,21.75,0,14.01,0z"/>
</svg>
</a></li>
  

  <!-- Twitter link -->
  
  <li class="icon-link-item"><a href="http://twitter.com/jglovier" class="icon-link" itemprop="url"><svg class="icon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
   viewBox="0 0 28 28" enable-background="new 0 0 28 28" xml:space="preserve" width="28">
<path id="Twitter" fill="#D1CECC" d="M14,0C6.27,0,0,6.27,0,14s6.27,14,14,14s14-6.27,14-14S21.73,0,14,0z M20.69,10.57
  c0.01,0.15,0.01,0.3,0.01,0.45c0,4.56-3.47,9.82-9.82,9.82c-1.95,0-3.76-0.57-5.29-1.55c0.27,0.03,0.54,0.05,0.82,0.05
  c1.62,0,3.11-0.55,4.29-1.48c-1.51-0.03-2.79-1.03-3.23-2.4c0.21,0.04,0.43,0.06,0.65,0.06c0.31,0,0.62-0.04,0.91-0.12
  c-1.58-0.32-2.77-1.71-2.77-3.39c0-0.01,0-0.03,0-0.04c0.47,0.26,1,0.41,1.56,0.43c-0.93-0.62-1.54-1.68-1.54-2.87
  c0-0.63,0.17-1.23,0.47-1.74c1.7,2.09,4.25,3.46,7.12,3.61c-0.06-0.25-0.09-0.52-0.09-0.79c0-1.91,1.55-3.45,3.45-3.45
  c0.99,0,1.89,0.42,2.52,1.09c0.79-0.15,1.53-0.44,2.19-0.84c-0.26,0.81-0.81,1.48-1.52,1.91c0.7-0.08,1.36-0.27,1.98-0.54
  C21.95,9.47,21.37,10.08,20.69,10.57z"/>
</svg>
</a></li>
  

  <!-- Dribbble link -->
  
  <li class="icon-link-item"><a href="https://dribbble.com/jag" class="icon-link" itemprop="url"><svg class="icon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
   viewBox="0 0 28 28" enable-background="new 0 0 28 28" xml:space="preserve" width="28">
<path id="Dribbble" fill="#D1CECC" d="M13.76,14.4c0.37-0.15,0.78-0.26,1.16-0.43c-0.18-0.34-0.35-0.73-0.5-1.04
  c-0.06-0.11-0.1-0.25-0.2-0.33c-2.49,0.72-5.25,1.17-8.48,1.16c-0.06,2.6,0.88,4.41,2.12,5.79C9.3,17.33,11.22,15.46,13.76,14.4z
   M15.45,15.38c-2.87,1.04-5.13,2.68-6.53,5.19c0.95,0.74,2.22,1.38,3.72,1.65c1.65,0.29,3.38-0.01,4.6-0.55
  c-0.37-2.12-0.97-4.14-1.65-5.92C15.57,15.62,15.57,15.46,15.45,15.38z M10.47,6.52c-2.3,1.15-3.92,2.99-4.58,5.79
  c2.87-0.04,5.42-0.39,7.66-1.04C12.58,9.64,11.6,8.01,10.47,6.52z M14.01,0C6.27,0,0,6.28,0,14.01s6.27,14.01,14.01,14.01
  c7.05,0,12.89-5.21,13.86-12c0.1-0.46,0.14-0.94,0.13-1.43c0.01-0.2,0.01-0.39,0.01-0.58C28.02,6.28,21.75,0,14.01,0z M21.17,20.6
  c-0.77,0.85-1.69,1.53-2.78,2.07c-1.09,0.55-2.33,0.97-3.8,1.04c-3.1,0.15-5.52-1.04-7.14-2.53c-1.66-1.53-2.92-3.59-3.14-6.56
  c-0.11-1.58,0.2-2.97,0.67-4.15c0.48-1.23,1.06-2.14,1.84-3.01c1.11-1.2,2.61-2.26,4.5-2.78c0.68-0.19,1.39-0.31,2.1-0.36
  c3.17-0.2,5.51,1.07,7.16,2.56c1.65,1.48,2.94,3.62,3.11,6.58C23.89,16.57,22.7,18.94,21.17,20.6z M17.05,14.98
  c0.64,1.86,1.23,3.76,1.59,5.9c0.46-0.26,0.86-0.61,1.24-0.99c1.14-1.15,1.99-2.63,2.33-4.55C20.79,14.91,18.79,14.7,17.05,14.98z
   M15.2,10.8c1.73-0.7,3.28-1.6,4.3-3.01c-1.36-1.14-3.32-2.18-5.82-2.05c-0.6,0.03-1.05,0.08-1.59,0.2
  c0.93,1.37,1.93,2.79,2.73,4.22C14.94,10.38,15.02,10.63,15.2,10.8z M15.81,12.06c0.2,0.38,0.39,0.81,0.56,1.19
  c0.06,0.14,0.08,0.31,0.2,0.41c1.93-0.22,4.06-0.06,5.74,0.28c-0.06-2.27-0.82-3.85-1.87-5.14C19.24,10.23,17.65,11.27,15.81,12.06z
  "/>
</svg>
</a></li>
  

  <!-- Facebook link -->
  

  <!-- LinkedIn link -->
  
  <li class="icon-link-item"><a href="https://www.linkedin.com/in/joelglovier" class="icon-link" itemprop="url"><svg class="icon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
   viewBox="0 0 28 28" enable-background="new 0 0 28 28" xml:space="preserve" width="28">
<path id="LinkedIn" fill="#D1CECC" d="M18.82,15.09v3.61h-2.09v-3.37c0-0.85-0.3-1.42-1.06-1.42c-0.58,0-0.92,0.39-1.07,0.77
  c-0.06,0.13-0.07,0.32-0.07,0.51v3.52h-2.09c0,0,0.03-5.71,0-6.3h2.09v0.89c0,0.01-0.01,0.01-0.01,0.02h0.01V13.3
  c0.28-0.43,0.77-1.04,1.89-1.04C17.79,12.25,18.82,13.16,18.82,15.09z M9.18,18.7h2.09v-6.3H9.18V18.7z M10.24,9.36
  c-0.72,0-1.19,0.47-1.19,1.09c0,0.61,0.45,1.09,1.16,1.09h0.01c0.73,0,1.18-0.48,1.18-1.09C11.39,9.84,10.95,9.36,10.24,9.36z
   M28,14c0,7.73-6.27,14-14,14S0,21.73,0,14S6.27,0,14,0S28,6.27,28,14z M20.93,8.02c0-0.55-0.46-1-1.02-1H8.09
  c-0.57,0-1.02,0.45-1.02,1v11.96c0,0.55,0.46,1,1.02,1h11.82c0.57,0,1.02-0.45,1.02-1V8.02z"/>
</svg>
</a></li>
  

  <!-- Instagram link -->
  

  <!-- Website link -->
  
  <li class="icon-link-item"><a href="http://joelglovier.com" class="icon-link" itemprop="url"><svg class="icon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
   viewBox="0 0 28 28" enable-background="new 0 0 28 28" xml:space="preserve" width="28">
<path id="Website" fill="#D1CECC" d="M14.83,7.6c0.03,0.08,0.03,0.14,0,0.19s-0.08,0.07-0.17,0.07c-0.12,0-0.26-0.01-0.4-0.04
  s-0.2-0.06-0.18-0.1c0.15-0.15,0.16-0.26,0.03-0.33c-0.13-0.07-0.27-0.11-0.42-0.11s-0.25-0.04-0.3-0.09s-0.03-0.09,0.05-0.09
  s0.22,0,0.4,0.01c0.19,0.01,0.31,0.04,0.37,0.08s0.17,0.1,0.33,0.19S14.8,7.52,14.83,7.6z M15.9,13.35c-0.11-0.03-0.2-0.03-0.26,0
  s-0.13,0.05-0.2,0.05c-0.08-0.01-0.25-0.09-0.5-0.24s-0.5-0.22-0.77-0.22c-0.11,0.01-0.17,0.04-0.19,0.08s-0.01,0.07,0.01,0.08
  c0.02,0.01,0.12,0.03,0.29,0.05s0.4,0.11,0.67,0.26c0.28,0.15,0.48,0.21,0.61,0.19s0.22-0.06,0.28-0.1
  c0.07-0.01,0.12-0.03,0.16-0.06S16.01,13.38,15.9,13.35z M13.62,6.85c0.17-0.03,0.3-0.13,0.38-0.3c0.03-0.14-0.04-0.2-0.21-0.18
  s-0.29,0.07-0.37,0.13c-0.01,0.03-0.02,0.06-0.03,0.09s-0.02,0.06-0.03,0.07l-0.08,0.1c-0.03,0.03-0.03,0.05-0.02,0.06
  C13.32,6.88,13.44,6.89,13.62,6.85z M16.12,7.08c-0.02-0.16-0.11-0.3-0.26-0.41s-0.32-0.19-0.5-0.22c-0.18-0.03-0.38-0.07-0.61-0.12
  s-0.4-0.04-0.53,0.04c-0.21,0.18-0.25,0.31-0.12,0.39c0.07,0.03,0.2,0.05,0.38,0.06s0.44,0.15,0.76,0.41
  c0.11,0.08,0.29,0.21,0.55,0.37s0.44,0.23,0.55,0.19c0.06-0.06,0.04-0.15-0.05-0.28S16.14,7.24,16.12,7.08z M28,14
  c0,7.73-6.27,14-14,14S0,21.73,0,14S6.27,0,14,0S28,6.27,28,14z M21.95,14c-0.06-2.25-0.83-4.12-2.33-5.62
  c-1.5-1.5-3.37-2.27-5.62-2.33c-2.25,0.06-4.12,0.83-5.62,2.33c-1.5,1.5-2.27,3.37-2.33,5.62c0.06,2.25,0.83,4.12,2.33,5.62
  c1.5,1.5,3.37,2.27,5.62,2.33c0.54,0,1.06-0.05,1.57-0.14c-0.11-0.07-0.17-0.24-0.18-0.51s0.04-0.52,0.16-0.76
  c0.15-0.26,0.3-0.61,0.46-1.04c0.15-0.43,0.08-0.77-0.23-1c-0.32-0.18-0.51-0.34-0.57-0.49s-0.19-0.32-0.37-0.54
  s-0.28-0.36-0.28-0.44v-0.21c-0.01-0.21,0.05-0.43,0.19-0.66l0.25-0.39c0.01-0.04,0.02-0.1,0.02-0.19v-0.19
  c-0.01-0.04-0.07-0.09-0.17-0.16s-0.17-0.1-0.22-0.1s-0.09,0.01-0.11,0.05s-0.07,0.06-0.13,0.06s-0.17-0.04-0.33-0.13
  c-0.16-0.09-0.27-0.16-0.32-0.21s-0.1-0.11-0.14-0.19s-0.09-0.15-0.16-0.22s-0.11-0.1-0.16-0.09s-0.12,0-0.23-0.03l-1.45-0.56
  c-0.26-0.11-0.43-0.23-0.5-0.37c-0.07-0.14-0.1-0.26-0.1-0.37s-0.06-0.23-0.17-0.37l-0.29-0.37c-0.08-0.12-0.14-0.24-0.17-0.34
  s-0.05-0.15-0.06-0.13c-0.01,0.07,0.02,0.23,0.1,0.48s0.12,0.39,0.1,0.43c-0.03,0.01-0.07-0.02-0.12-0.11s-0.12-0.19-0.19-0.3
  c-0.06-0.07-0.07-0.15-0.04-0.25c0.03-0.1-0.07-0.38-0.29-0.85c-0.22-0.47-0.26-0.85-0.11-1.15s0.24-0.57,0.3-0.82
  c0.03-0.21,0.09-0.25,0.19-0.13c0.1,0.12,0.1,0.11,0.02-0.01c-0.08-0.18-0.11-0.4-0.08-0.65c0.03-0.26,0.01-0.46-0.06-0.61
  c-0.11-0.1-0.3-0.08-0.58,0.05S9.12,8.14,9.1,8.16c0.03-0.12,0.18-0.28,0.46-0.46l0.87-0.58c0.26-0.17,0.49-0.22,0.69-0.17
  s0.41,0.12,0.62,0.21s0.34,0.12,0.37,0.1s0.01-0.06-0.06-0.13s-0.07-0.13,0.01-0.16S12.26,6.96,12.43,7
  c0.17,0.03,0.31,0.11,0.42,0.24s0.3,0.18,0.54,0.17s0.32,0.01,0.25,0.06s-0.11,0.12-0.11,0.19c0.04,0.06,0.02,0.1-0.05,0.13
  s-0.2,0.1-0.36,0.21s-0.18,0.19-0.05,0.26c0.13,0.07,0.36,0.21,0.67,0.41c0.28,0.19,0.41,0.19,0.41-0.01s-0.02-0.4-0.06-0.61
  c-0.01-0.14,0.05-0.19,0.2-0.14s0.22,0.07,0.24,0.08c0.17,0.11,0.27,0.15,0.32,0.11s0.13-0.04,0.26-0.01
  c0.17,0.07,0.37,0.19,0.6,0.37l0.41,0.33c-0.43,0.25-0.6,0.41-0.51,0.49s0.2,0.14,0.32,0.2c0.06,0.06,0.02,0.12-0.1,0.21
  s-0.2,0.12-0.23,0.12c-0.08-0.08-0.15-0.1-0.2-0.05s-0.1,0.09-0.16,0.13c-0.06,0.04-0.07,0.09-0.05,0.14s0.04,0.09,0.05,0.1
  c-0.3,0.07-0.47,0.22-0.49,0.44s-0.02,0.39-0.01,0.49c0,0.08-0.07,0.18-0.21,0.3s-0.24,0.23-0.31,0.34c-0.03,0.14,0,0.29,0.08,0.47
  c0.08,0.17,0.08,0.27,0,0.3c-0.08-0.01-0.22-0.12-0.41-0.32c-0.19-0.2-0.55-0.24-1.08-0.13c-0.19,0.04-0.39,0.16-0.6,0.36
  s-0.23,0.49-0.06,0.88c0.21,0.32,0.43,0.38,0.68,0.19c0.25-0.19,0.43-0.3,0.56-0.31c0.1,0.08,0.12,0.2,0.06,0.35
  c-0.06,0.15-0.08,0.24-0.08,0.27c0.06-0.01,0.17,0.02,0.34,0.09s0.28,0.27,0.32,0.58c0.04,0.31,0.19,0.49,0.46,0.55
  s0.45,0.08,0.57,0.07s0.28-0.09,0.48-0.24s0.32-0.24,0.37-0.27s0.17-0.06,0.35-0.1s0.47,0.03,0.84,0.23s0.67,0.31,0.88,0.35
  s0.38,0.11,0.5,0.2s0.18,0.2,0.18,0.33s0.05,0.23,0.14,0.3c0.15,0.04,0.39,0.07,0.72,0.07s0.57,0.1,0.72,0.28
  c0.07,0.28-0.08,0.73-0.46,1.38c-0.37,0.64-0.68,1.05-0.93,1.23c-0.18,0.12-0.34,0.29-0.48,0.49s-0.3,0.38-0.49,0.55
  s-0.41,0.34-0.66,0.52s-0.51,0.34-0.78,0.5c-0.21,0.15-0.36,0.32-0.46,0.51s-0.19,0.32-0.27,0.4c1.81-0.43,3.28-1.34,4.43-2.75
  C21.31,17.6,21.9,15.93,21.95,14z"/>
</svg>
</a></li>
  

</ul>


        </div>

        <div class="executive-summary no-print" itemprop="description">
          <p>This is the executive summary. You should write a few brief, concise, and meaningful sentences about yourself from a professional context, and your immediate career goals. Make the length appropriate for your needs, but K.I.S.S.</p>
        </div>

        
        <a href="mailto:homerjsimpson@youremailaddress.com" class="contact-button no-print" itemprop="email">Contact me</a>
        

      </header>

      
      <!-- begin Experience -->
      <section class="content-section">

        <header class="section-header">
          <h2>Experience</h2>
        </header>

        
        <div class="resume-item" itemscope itemprop="worksFor" itemtype="http://schema.org/Organization">
          <h3 class="resume-item-title" itemprop="name">Springfield Nuclear Power Plant</h3>
          <h4 class="resume-item-details" itemprop="description"><span style="display: block; float:left;">Safety Inspector</span><span style="display: block; float:right;">Nov, 1980 &mdash; Present</span></h4><br/>
          <p class="resume-item-copy" style="clear: both;">Write about your core competencies in one or two sentences describing your position. If you held the position for a long time, it could be a longer section, including a couple bullet points	<ul class="resume-item-list"><li>Ate lots of donuts</li><li>Fell asleep rarely</li><li>Left promptly at end of day (sometimes earlier)</li></ul></p>
        </div><!-- end of resume-item -->
        
        <div class="resume-item" itemscope itemprop="worksFor" itemtype="http://schema.org/Organization">
          <h3 class="resume-item-title" itemprop="name">Sir Putt-A-Lot's Merrie Olde Fun Centre</h3>
          <h4 class="resume-item-details" itemprop="description"><span style="display: block; float:left;">Safety Inspector</span><span style="display: block; float:right;">Jun, 1978 &mdash; Sept, 1979</span></h4><br/>
          <p class="resume-item-copy" style="clear: both;">If your stint was shorter, feel free to be brief and just call out the most meaningful points of your role. Be concise, and be meaninful. The person reading just needs enough to want to talk to you more about your experience.</p>
        </div><!-- end of resume-item -->
        
        <div class="resume-item" itemscope itemprop="worksFor" itemtype="http://schema.org/Organization">
          <h3 class="resume-item-title" itemprop="name">Simpson Lazer Tag</h3>
          <h4 class="resume-item-details" itemprop="description"><span style="display: block; float:left;">Front Desk Attendant</span><span style="display: block; float:right;">Jun, 1975  &mdash; May, 1978</span></h4><br/>
          <p class="resume-item-copy" style="clear: both;">Boy, when Marge first told me she was going to the Police Academy, I thought it would be fun and exciting, you know, like the movie... Spaceballs. But instead, it's been painful and disturbing, like the movie Police Academy.</p>
        </div><!-- end of resume-item -->
        

      </section>
      <!-- end Experience -->
      


      
      <!-- begin Education -->
      <section class="content-section">
        <header class="section-header">
          <h2>Education</h2>
        </header>

        
        <div class="resume-item" itemscope itemprop="worksFor" itemtype="http://schema.org/CollegeOrUniversity">
          <h3 class="resume-item-title" itemprop="name">Springfield College</h3>
          <h4 class="resume-item-details" itemprop="description"><span style="display: block; float:left;">Associates Degree, Business Management</span><span style="display: block; float:right;">1984 &mdash; 1986</span></h4>
          <h5 class="resume-item-details" itemprop="description">Quickest to fall asleep</h5>
          <p class="resume-item-copy">If you had any meaningful roles at college, feel free to write about them here</p>
        </div>
        
      </section>
      <!-- end Education -->
      


      
      <!-- begin Projects -->
      <section class="content-section">
        <header class="section-header">
          <h2>Projects</h2>
        </header>

        
        <div class="resume-item" itemscope itemprop="worksFor" itemtype="http://schema.org/Organization">
          <h3 class="resume-item-title" itemprop="name">donutfinder.io</h3>
          <h4 class="resume-item-details" itemprop="description"><span style="display: block; float:left;">Founder & Primary Developer</span><span style="display: block; float:right;">2012 &mdash; Present</span></h4><br/>
          <p class="resume-item-copy" style="clear: both;">Donut Locator is an open source node/ember app that lets users find donuts within a defined radius from their home.</p>
        </div>
        
        <div class="resume-item" itemscope itemprop="worksFor" itemtype="http://schema.org/Organization">
          <h3 class="resume-item-title" itemprop="name">Springfield Donut Eater's User Group</h3>
          <h4 class="resume-item-details" itemprop="description"><span style="display: block; float:left;">Co-Founder & Organizer</span><span style="display: block; float:right;">2007 &mdash; Present</span></h4><br/>
          <p class="resume-item-copy" style="clear: both;">DEUG is a local monthly meetup in Springfield where we share all the latest tips and tricks for dat donut lifestyle. I organize the group, and typically eat most of the donuts.</p>
        </div>
        

      </section>
      <!-- end Projects -->
      

      
      <!-- begin Skills -->
      <section class="content-section">

        <header class="section-header">
          <h2>Skills</h2>
        </header>
        
        <div class="resume-item">
          <h4 class="resume-item-details">Donut design</h4>
          <p class="resume-item-copy">Sprinkle art, icing design, eclair management, taste testing, donut/coffee pairing research</p>
        </div>
        
        <div class="resume-item">
          <h4 class="resume-item-details">Craft beer brewing</h4>
          <p class="resume-item-copy">Hops inspection, brew testing, distribution management, bottle label design, festival and event management</p>
        </div>
        
        <div class="resume-item">
          <h4 class="resume-item-details">Family leadership</h4>
          <p class="resume-item-copy">Bread winning, conflict resolution, couch inspection, TV longevity testing</p>
        </div>
        

      </section>
      <!-- end Skills -->
      

      
      <!-- begin Recognition -->
      <section class="content-section">

        <header class="section-header">
          <h2>Recognition</h2>
        </header>

        
        <div class="resume-item">
          <h3 class="resume-item-title" itemprop="award">Outstanding Achievement</h3>
          <h4 class="resume-item-details"> &bull; 2010</h4>
          <p class="resume-item-copy">Awarded for stopping a nuclear meltdown, even though I also started it.</p>
        </div>
        
        <div class="resume-item">
          <h3 class="resume-item-title" itemprop="award">Duff Beer Customer of the year</h3>
          <h4 class="resume-item-details"> &bull; 1997 &mdash; 2001, 2003, 2008 &mdash; 2012</h4>
          <p class="resume-item-copy">Honored by <a href="https://en.wikipedia.org/wiki/Duff_Beer">Duff Beer</a> for being an outstanding customer several years straight. Qualifications included most beer consumed at a bar, most beer purchased, and most beer ralphed.</p>
        </div>
        
        <div class="resume-item">
          <h3 class="resume-item-title" itemprop="award">Moe's Patron of the Month</h3>
          <h4 class="resume-item-details"> &bull; 12/2001, 8/2004</h4>
          <p class="resume-item-copy">Specifically this prestigious awarded twice for stopping a robber with my belly.</p>
        </div>
        

      </section>
      <!-- end Recognition -->
      

      
      <!-- begin Associations -->
      <section class="content-section">

        <header class="section-header">
          <h2>Associations</h2>
        </header>

        
        <div class="resume-item">
          <h3 class="resume-item-title"><a href="http://beerfortheworld.com"></a></h3>
          <h4 class="resume-item-details">Volunteer &bull; 2008 &mdash; Present</h4>
          <p class="resume-item-copy">Organized fund drives and participated in fundraising events for the benefit of families in third world countries without proper access to malt beverages.</p>
        </div>
        
        <div class="resume-item">
          <h3 class="resume-item-title"><a href="http://beerfortheworld.com"></a></h3>
          <h4 class="resume-item-details">Member in Good Standin &bull; 1994 &mdash; Present</h4>
          <p class="resume-item-copy">Founding member of the local nuclear workers labor union.</p>
        </div>
        

      </section>
      <!-- end Associations -->
      

      
      <!-- begin Links -->
      <section class="content-section">

        <header class="section-header">
          <h2>Additional Links</h2>
        </header>

        <div class="resume-item">
          <ul class="resume-item-list">
            
            <li><a href=#>Springfield Poker Club</a></li>
            
            <li><a href=#>Springfield Donut Eater's User Group</a></li>
            
          </ul>
        </div>

      </section>
      <!-- end Links -->
      

      
      <!-- begin Print Social Links -->
      <section class="content-section print-only">

        <header class="section-header">
          <h2>Social Links</h2>
        </header>

        <div class="resume-item">
        <!-- and guess where these are defined? Yup, you guessed it: the _config.yml file -->

<ul>

  <!-- GitHub link -->
  
  <li><strong>Github</strong>: https://github.com/jglovier/resume-template</li>
  

  <!-- Twitter link -->
  
  <li><strong>Twitter</strong>: http://twitter.com/jglovier</li>
  

  <!-- Dribbble link -->
  
  <li><strong>Dribbble</strong>: https://dribbble.com/jag</li>
  

  <!-- Facebook link -->
  

  <!-- LinkedIn link -->
  
  <li><strong>LinkedIn</strong>: https://www.linkedin.com/in/joelglovier</li>
  

  <!-- Instagram link -->
  

  <!-- Website link -->
  
  <li><strong>Website</strong>: http://joelglovier.com</li>
  

</ul>


        </div>

      </section>
      <!-- end Print Social Links -->
      

      <footer class="page-footer">
        <p class="footer-line">Made by <a href="http://twitter.com/jglovier">@jglovier</a>. Fork me on <a href="https://github.com/jglovier/resume-template">GitHub</a>.</p>
        <p class="footer-line">If this is your live resume, you can modify or remove this part. ;-)</p>
      </footer>

    </div>

  </body>

</html>
