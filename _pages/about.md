---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Hi, I’m Amer Essakine. I’m a 4th-year student in the Mathematics department at ENS Paris-Saclay. I recently finished the MVA master’s program, where I took courses like Reinforcement Learning, Theory of Deep Learning, Computer Vision, Generative Models, and Graphs in ML. I’m about to start a research internship at Université Laval with Prof. Audrey Durand.

I’m interested in all kind of research in applied mathematics and machine-learning research—especially reinforcement learning. My focus includes exploration, policy selection, risk-sensitive RL, self-supervised RL and bandits plus any paper that connect solid theory with useful algorithms.

I did multiple research internships in diverse fields of machine learning. I am currently applying to PhD programs, preferably in reinforcement learning, but, like any early-career student researcher, I am open to other fields.


Internship about risk-sensitive reinforcement learning
======
During my MVA master, I conducted a research internship under the supervision Prof. Claire Vernade at the Tübingen AI Center on risk-sensitive reinforcement learning. My work addressed best-policy identification for the entropic risk measure, where I derived lower bounds and proposed a Kullback–Leibler–driven exploration algorithm to tighten them.

This line of work is ongoing, with a manuscript in preparation and a planned submission to COLT 2026.

Here's my master report: [Master’s Report (PDF)]({{ '/files/MVA report.pdf' | relative_url }}) and my master presentation: [Master’s presentation (PDF)]({{ '/files/MVA presentation.pdf' | relative_url }})

Internship about Implicit Neural representation
======
At the University of Cambridge, I undertook a research internship under the supervision of Dr. Angelica Aviles-Rivero. I led a comprehensive review and benchmark of various approaches to implicit neural representations, detailing their mathematical properties and underlying motivations. This work resulted in the survey “Where Do We Stand with Implicit Neural Representations? A Technical and Performance Survey,” which was accepted at TMLR.

As a side note, based on a link between an existing method and sampling theory, I introduced WIREN (Walsh Implicit Neural Network), which generalizes the approach by using the inverse Fourier transform of Walsh functions as the activation function, improving the accuracy on tasks like CT reconstruction.

Here's the TMLR paper [Paper (PDF)](https://arxiv.org/pdf/2411.03688), my master report: [Master’s Report (PDF)]({{ '/files/M1 report.pdf' | relative_url }}) and my master presentation: [Master’s presentation (PDF)]({{ '/files/M1 presentation.pdf' | relative_url }})


Internship about STGCN
======
At ENS Paris-Saclay (Centre Borelli), I completed an introductory research internship on forecasting regional electricity demand. I assembled a half-hourly dataset for 12 French regions (2014–2018) with consumption and temperature, and built ARIMA and GAM baselines—GAM clearly beat ARIMA (≈2% vs ≈26% MAPE). I then implemented spatio-temporal graph convolutional networks (STGCN) to capture spatial effects, testing graph choices including identity, spatial proximity, correlation, and a learned Laplacian (FGL-3SR).

Here's my report in french [Report (PDF)]({{ '/files/L3 report.pdf' | relative_url }}) and my presentation [Presentation (PDF)]({{ '/files/L3 presentation.pdf' | relative_url }})

Junior assitant at CentraleSupelec 
========
During the last year, I had the chance to give tutorial courses to students in the 2nd-year Bachelor program (O.G.E.) - CentraleSupélec x McGill. The sessions were given to a group of 13 students throughout the year, and the courses included linear algebra, topology, differential calculus, and functional analysis. This was a very instructive experience for me. It was my first teaching experience, and it showed that you cannot fully understand something until you try to explain it to someone; only then do you figure out the intuition behind everything.
