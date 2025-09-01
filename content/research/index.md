---
title: Research
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 
        content: 
        align: left
        background:
          image:
            filename: slide1.jpg
            filters:
              brightness: 0.5
          position: right
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: false
      slide_height: "25vh"
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 7000

  - block: markdown
    id: research-grid
    content:
      title: "Research"
      subtitle: ""
      text: |-
        <div class="container-xl px-0" style="max-width: 1200px;">
          <div class="row g-4">
            <!-- Col 1: IMAGE (moved up) -->
            <div class="col-12 col-md-6 col-lg-4">
              <div class="d-flex flex-column h-100">
                <h5 class="mb-2 text-muted text-sentencecase text-center" style="letter-spacing:.02em;">Molecular Signaling Networks that Govern (Myo)fibroblast Plasticity</h5>
                <div class="ratio ratio-1x1 rounded-3 overflow-hidden">
                  <img src="/files/figure1.jpg" alt="Figure 1" class="w-100 h-100" style="object-fit: cover;">
                </div>
                <p class="mt-3 mb-0">
                  Our cells have the remarkable ability to sense and respond to a wide range of microenvironment cues—including both biochemical signals and mechanical stimuli—but how exactly these combined inputs are processed simultaneously remains incompletely understood. In the Cho Lab, we study under what circumstances soluble and insoluble cues <strong>synergize with or antagonize each other</strong>, and how this crosstalk affects or directs: (i) cell state plasticity, (ii) sex- and disease-specificity, and (iii) intercellular communication mechanisms in fibrotic remodeling and tissue repair.  
                </p>
              </div>
            </div>
            <!-- Col 2: VIDEO (now in the middle) -->
            <div class="col-12 col-md-6 col-lg-4">
              <div class="d-flex flex-column h-100">
                <h5 class="mb-2 text-muted text-sentencecase text-center" style="letter-spacing:.02em;">Cardiovascular Engineering Across Multiple Scales</h5>
                <div class="ratio ratio-1x1 rounded-3 overflow-hidden">
                  <video class="w-100 h-100" autoplay loop muted playsinline preload="metadata" style="object-fit: cover; background:#000;">
                    <source src="/files/figure2.mp4" alt="Figure 2" type="video/mp4">
                  </video>
                </div>
                <p class="mt-3 mb-0">
                  Our team has extensive expertise in human induced pluripotent stem cell (iPSC)-based engineered tissues as well as several animal models. We routinely work with: (i) cells cultured on tunable biomaterials, (ii) arrays of multi-cell type cardiac organoids and spheroids, (iii) engineered heart tissue and heart-on-a-chip models, (iv) <em>ex vivo</em> chick embryonic hearts, and (v) several mouse disease models. For every biological phemonon we study, we take a <strong>systems-level approach</strong> to examine, engineer, characterize, manipulate, and cross-validate across multiple scales. 
                </p>
              </div>
            </div>
            <!-- Col 3: IMAGE -->
            <div class="col-12 col-md-6 col-lg-4">
              <div class="d-flex flex-column h-100">
                <h5 class="mb-2 text-muted text-sentencecase text-center" style="letter-spacing:.02em;">Bioinformatics/AI-guided Precision Medicine</h5>
                <div class="ratio ratio-1x1 rounded-3 overflow-hidden">
                  <img src="/files/figure3.jpg" alt="Figure 3" class="w-100 h-100" style="object-fit: cover;">
                </div>
                <p class="mt-3 mb-0">
                  We combine molecular tools with cutting-edge multi-omics (scRNA- & scATAC-seq, spatial, and proteomics) and AI-based methods to enable new druggable target identification, conduct large-scale <em>in silico</em> drug screening, map protein interactomes, and perform transcription factor activity fingerprinting. We are particularly interested in applying such tools to better characterize the functional diversity and state plasticity of cardiac stomal populations across various disesase states—a critical challenge for the development of <strong>precision anti-fibrotic therapies</strong>.
                </p>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['25px','0','65px','0']
      background:
        color: 'transparent'
      css_class: "bg-transparent"
      css_style: "background-color: transparent;"


  - block: markdown
    id: research-video
    content:
      title: "Recorded Talks"
      subtitle: "Check out our recent presentation at the Bay Area Cardiovascular Symposium"
      text: |
        <div class="video-embed">
          <iframe
            src="https://www.youtube-nocookie.com/embed/JvKEGdhMNB0?rel=0&modestbranding=1"
            title="YouTube video"
            loading="lazy"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen
          ></iframe>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['10px','0','10px','0']
      # optional: center the heading + video block and limit its width
      css_class: text-center
      css_style: "max-width: 900px; margin: 0 auto;"


---
