<!-- .slide: style="text-align: left;" -->

<div style="position: relative; height: 500px;">

<h1 style= "position: absolute; top: 0; left: 0;">
Journal club
</h1>

<p style="position: absolute; bottom: 0; right: 0;">
Research work overview
</p>
</div>




<!-- .slide: style="text-align: left;" -->

### Paper: Spatiotemporal dynamics of capillary rise in shallow groundwater table areas revealed by spatial TDR

<div style="display: flex; align-items: flex-start; gap: 20px;">
<a href="https://doi.org/10.1016/j.jhydrol.2026.135957"
   target="_blank"
   rel="noopener noreferrer"
   style="display: block; flex: 0 0 45%;">
  <img src="md_presentations/images/image.png"
       alt="paper image"
       style="display: block; width: 100%; max-width: 100%; margin: 0;">
</a>
  <div style="flex: 1; text-align: left;">
    <p style="margin-top: 0;">Key points</p>
    <ul>
      <li>Time Domain Reflectometry (TDR)</li>
      <li>Spatial waveguides</li>
      <li>Spatial TDR – Inverse modeling</li>
      <li>Capillary rise</li>
    </ul>
  </div>
</div>


</div>

Note: First slide of the Paper 1 presentation

--
<!-- .slide: style="text-align: left; height: 100%; box-sizing: border-box; overflow-y: auto; overscroll-behavior: contain;" -->
### Introduction

- #### The conceptualization of groundwater table 

    ![Homogeneous aquifer](md_presentations/images/homogeneous_isotropic.png) <!-- .element: style="width: 33%; height: 350px; object-fit: contain;" -->![Capillary rise](md_presentations/images/capillary_rise.png)<!-- .element: style="width: 33%; height: 350px; object-fit: contain;" -->![Blocky structure image image](md_presentations/images/blocky_clay_soil.png) <!-- .element: style="width: 33%; height: 350px; object-fit: contain;"-->
    
    [The water table: Its conceptual basis, its measurement and its usefulness as a hydrological variable](https://onlinelibrary.wiley.com/doi/abs/10.1002/hyp.14622)

    
    ![Saturated_capillary_rise](md_presentations/images/saturated_capillary_rise.png)<!-- .element: style="display: block; width: 50%; height: 400px; object-fit: contain; margin: 0 auto;" -->

     [Rate of Capillary Rise in Soil](https://sci-hub.box/10.1061/(asce)1090-0241(2004)130:6(646))
    
- #### Soil volumetric content sensors 
    **Point sensor**
    ![Point sensors](md_presentations/images/point_sensor.jpg)<!-- .element: style="display: block; width: 50%; height: 400px; object-fit: contain; margin: 0 auto;" -->

    Robust and reliable data, however,
    the placement of the sensors in great depths below the soil surface:
    1. time consuming,
    2. essential disturbance of soil structure,

    may lead to erroneous conclusions about the observed hydrological phenomena.

    **Multi-depth sensor**
    ![profiler](md_presentations/images/profiler.webp)<!-- .element: style="display: block; width: 50%; height: 400px; object-fit: contain; margin: 0 auto;" -->

    Commercial applications of TDR and FDR profile probes allow the vertical installation to a maximum depth of 1 m below surface ([Babaeian et al., 2025](https://onlinelibrary.wiley.com/doi/abs/10.1002/vzj2.70060); [Nieberding et al., 2023](https://onlinelibrary.wiley.com/doi/abs/10.1002/vzj2.70093)). 
    1. Provide 6 – 9 measurements within the installation depth, 
    2. Spatial resolution: acceptable for conventional agricultural applications, 
    3. Monitoring of complex hydrological processes, such as capillary rise, requires high spatial and temporal resolution of θ even in greater than 1 m depths above shallow groundwater tables. 
    4. In parallel acquisition of soil hydraulic properties till the depth of probe installation ensure the accurate interpretation of sensor values.

- #### Waveform reconstruction – Inverse modeling

    ![TDR instrument, pulse generator and oscilloscope, three-rod probe, incident and reflected waveforms, and equivalent transmission-line circuit, with English labels](md_presentations/images/tdr_waveform_reconstruction_en_v2.png) <!-- .element: style="display: block; width: 100%; max-width: 100%; height: auto; margin: 12px auto;" -->

    **TDR measurement setup**

    - TDR instrument: synchronized pulse generator and oscilloscope.
    - BNC connector and 50 Ω coaxial cable connected to a three-rod probe.

    **Waveforms**

    - Incident signal, reflected signal, and signal superposition.
    - Voltage plotted against time; the diagram marks the travel time in the three-rod probe.

    **Equivalent transmission-line circuit**
    - Parameters: 
        1. the ohmic resistance of the line (R [Ω/m]), which arises from conductor losses due to the finite conductivity of the conductors;
        2. the inductance of the line (L [H/m]), which results from the magnetic fields generated around the waveguides when current flows through them and alters current intensity; 
        3. the conductance of the line (G [S/m]), which is associated with dielectric losses; 
        4. and the capacitance of the line (C [F/m]), which is caused by the proximity of two conductors.
    - Series elements: R and L; shunt elements: G and C.
    - Voltage and current at positions x and x + Δx: V(x), I(x), V(x + Δx), and I(x + Δx).


- #### Study objective
    The objective of this study is to explicitly determine the expansion of the saturated portion of the capillary fringe ([Lu and Likos, 2004](https://sci-hub.box/10.1061/(asce)1090-0241(2004)130:6(646))) in SGT areas by developing and deploying an extended in–situ monitoring system.
--
<!-- .slide: style="text-align: left; height: 100%; box-sizing: border-box; overflow-y: auto; overscroll-behavior: contain;" -->
### Materials and Methods 
- #### Study area
![Study area](md_presentations/images/study_map.png) <!-- .element: style="width: 45%; height: 350px; object-fit: contain;" -->![Lithostratigraphy](md_presentations/images/lithostratigraphy.png)<!-- .element: style="width: 45%; height: 350px; object-fit: contain;" -->

- #### Experimental crop – Study setup
    ![Study_setup](md_presentations/images/study_setup.png)
    - Spatial waveguides installed in the field (SP1, SP2, SP3, SP4 and SP5) constitute transmission lines of insulated flexible flat copper wires, which resolve signal attenuation emerging with the use of conventional uninsulated transmission lines in depths below 1 m from the soil surface.
    - The monitoring period of the measurement assembly (Campbell TDR100– Campbell SDM8X50 multiplexer – Campbell CR800), connected to the coaxial cable–waveguide system, extended from 23 June 2024 to 27 June 2024, using a 3-hour measurement interval.
- #### Sensor installation

    Commercial θ profilers provide installation instructions: 
    1. avoid gaps between the probe and the surrounding soil matrix – screw type installation [soilvue10, 2026](https://s.campbellsci.com/documents/us/manuals/soilvue10.pdf), 
    2. While this process ensures gapless contact between the probe and the soil profile, do not take into account the findings of previous research with conventional rod probes insisting that soil disturbance and in particular compaction induced by pushing probes into the soil could entail significant error to θ measurements due to disturbance of soil pores ([Iwata et al., 2017](https://onlinelibrary.wiley.com/doi/abs/10.1111/ejss.12493); [Rothe et al., 1997](https://onlinelibrary.wiley.com/doi/abs/10.1029/97WR00677)). Drilling the soil before probe installation form a solution to reduce the compaction effect as the disturbance of soil matrix is minimized ([Rothe et al., 1997](https://onlinelibrary.wiley.com/doi/abs/10.1029/97WR00677)).

    ![sensor](md_presentations/images/sensor.jpg)<!-- .element: style="display: block; width: 100%; height: 400px; object-fit: contain; margin: 0 auto;" -->

- #### Field work

<div style="display: flex; align-items: center; gap: 20px;">
  <img src="md_presentations/images/drill.jpg"
       alt="Left photo"
       style="width: 28%; max-height: 320px; object-fit: contain; margin: 0;">

  <video controls
         style="width: 100%; max-height: 350px; min-width: 0;">
    <source src="md_presentations/videos/eijkelkamp.mp4" type="video/mp4">
  </video>

  <video controls
         style="width: 100%; max-height: 350px; min-width: 0;">
    <source src="md_presentations/videos/drilling.mp4" type="video/mp4">
  </video>

  <img src="md_presentations/images/liner.jpg"
       alt="Right photo"
       style="width: 100%; max-height: 350px; object-fit: contain; margin: 0;">
</div>

- Electrical percussion hammer (Eijekelkamp)
- Soil storage in transparent PVC liner
- Soil catcher is placed before percussion gouges
- Sampling volume: $1.66 \cdot 10^3 cm^3$

- #### Waveform reconstruction algorithm – Processing of retrieved waveforms
    ![UML](md_presentations/images/uml.png)

    Source code (pyTDR) is deposited in a GitHub repository (https:// github.com/efthymios19/pyTDR/tree/main), where can be downloaded together with aninteractive notebook example. To explain the class functions for inverse modeling, a detailed example involving measurements in dry sand is used (Text S7).

- #### Recalibration of Topp equation for insulated waveguides – Uncertainty analysis of spatial TDR profiles

    The original Topp equation ([Topp et al., 1980](https://onlinelibrary.wiley.com/doi/abs/10.1029/WR016i003p00574)) was calibrated for ∊r = 1 (air) and∊r = 80 (water), corresponding to the dielectric constants of these materials at room temperature and a frequency of 1 kHz.  However, the presence of dielectric insulation in the installed waveguides leads to reduced measured values of ∊r in water (~28 for 0.5 m waveguides and ~ 20 for 1 m waveguides), due to the reduced measurement volume ([Ferre et al., 1996](https://onlinelibrary.wiley.com/doi/abs/10.1029/95WR02576); [Knight et al., 1997](https://onlinelibrary.wiley.com/doi/abs/10.1029/97WR00435)). In contrast, ∊r values in air range between 1.4 and 1.5 for waveguides of length 0.5–1 m, showing only minor deviation from reference values.

    To quantify uncertainty propagated to the final outcomes of the waveform reconstruction, both θ profiles–timeseries and identification of the expansion of the saturated portion of capillary fringe, from inverse modeling and recalibration of Topp’s deterministic equation, Monte Carlo uncertainty analysis was conducted ([Huisman et al., 2008](https://onlinelibrary.wiley.com/doi/abs/10.2136/vzj2007.0139)).

    For each spatial waveguide and timestep, the inverse modeling process provided an apparent ∊r(z, t) profile with the corresponding depth vector z(t). The calibrated Topp equation was then applied to convert ∊r(z, t) to θ for each available segment across the transmission lines. Uncertainty was evaluated by repeatedly perturbing the uncertain input quantities (**Waveform inversion, Start-end point identification, calibration–parameter uncertainty, Point-sensor uncertainty, Porosity uncertainty, Installation disturbance, Calibration residual uncertainty, Saturated conditions threshold uncertainty**) and recalculating the resulting θ profile. The 5th, 50th, and 95th percentiles of the Monte Carlo ensemble were used to represent the lower bound, median estimate, and upper bound of the propagated uncertainty interval.

    ![threshold](md_presentations/images/thres.png)
--
<!-- .slide: style="text-align: left; height: 100%; box-sizing: border-box; overflow-y: auto; overscroll-behavior: contain;" -->
### Results – Discussion
- #### Recalibration of Topp equation
![Topp equation](md_presentations/images/topp_eq.png)

- #### Calibration – Field consistency evaluation
![Calibration](md_presentations/images/calibration.png)

- #### Uncertainty analysis
![Uncertainty](md_presentations/images/uncertainty.png)

Local θ uncertainty is mainly influenced by porosity, point sensor accuracy, installation effects, and calibration residuals. In contrast, the inferred saturated depth is more sensitive to calibration–parameter uncertainty and waveform–inversion uncertainty because it depends on the first crossing of an operational saturation threshold. Therefore, the retrieved profiles provide robust information on the temporal evolution and spatial pattern of θ across the waveguides, but the exact depth of the saturated portion of the capillary fringe should be interpreted within the reported uncertainty interval. However, the large uncertainty intervals on the inferred saturation depth do not indicate large uncertainty in the retrieved θ profiles. Instead, the larger depth uncertainty arises because the saturated depth is defined by a threshold crossing. When θ(z,t) remains close to α n(z) over a depth interval, small perturbations in θ can shift the first detected crossing depth. Therefore, the saturated boundary is better interpreted as a transition zone, whereas the retrieved θ profiles remain robust for evaluating θ fluctuations.

- #### Meteorological – Hydrological conditions within the experimental crop
![meteo](md_presentations/images/meteo.png)

- #### $\theta$ profiles
![profiles](md_presentations/images/profiles.png)

![probability](md_presentations/images/probability.png)
--
<!-- .slide: style="text-align: left; height: 100%; box-sizing: border-box; overflow-y: auto; overscroll-behavior: contain;" -->
### Conclusions
- The study demonstrated an integrated sensor system for monitoring soil water content dynamics and capillary rise in shallow groundwater environments using spatial TDR.

- The approach combines:

    1. inverse modeling of TDR waveforms
    2. automated Python-based signal processing
    3. dielectric profile reconstruction
    4. calibration against discrete soil moisture sensors
    5. physically constrained scaling using soil properties
    6. uncertainty propagation

- The method enables retrieval of high-resolution soil water content profiles along the full monitored soil profile.

- Spatial TDR was able to capture fine-scale soil heterogeneity and transient capillary rise responses linked to  diurnal groundwater table fluctuations.

- The results show that conventional discrete sensors may miss important spatial variability in the unsaturated zone–groundwater continuum.

- The observed coupling between groundwater table dynamics and soil moisture fluctuations highlights the importance of capillary processes in shallow groundwater table areas.

- Extending the monitoring period could improve applications related to:

    1. irrigation management
    2. evapotranspiration estimation
    3. groundwater abstraction strategies

- Overall, spatial TDR combined with automated inversion and calibration tools provides a promising way to bridge the gap between point-scale measurements and profile-scale hydrological processes.





<!-- .slide: style="text-align: left;" -->

### Paper: A Framework for Monitoring Soil Hydraulic Properties of Undisturbed Soil Samples and Modeling Unsaturated Zone Water Flow

<div style="display: flex; align-items: flex-start; gap: 20px;">
<a href="https://doi.org/10.1007/s40710-025-00791-1"
   target="_blank"
   rel="noopener noreferrer"
   style="display: block; flex: 0 0 45%;">
  <img src="md_presentations/images/framework_undisturbed.png"
       alt="paper image"
       style="display: block; width: 100%; max-width: 100%; margin: 0;">
</a>
  <div style="flex: 1; text-align: left;">
    <p style="margin-top: 0;">Key points</p>
    <ul>
      <li>Undisturbed soil sampling </li>
      <li> Centrifuge method</li>
      <li>Bimodal hydraulic equations</li>
      <li>Unsaturated zone modeling</li>
      <li>Data assimilation</li>
    </ul>
  </div>
</div>
</div>

--
<!-- .slide: style="text-align: left;" -->
#### Soil column – Ksat

![Falling-head permeameter method: sample preparation, cell design and dimensions, and laboratory setup, translated into English](md_presentations/images/falling_head_permeameter_en.png) <!-- .element: style="display: block; width: 100%; max-width: 100%; max-height: 520px; object-fit: contain; margin: 0 auto;" -->

--
<!-- .slide: style="text-align: left;" -->
#### Soil hydraulic properties by depth
![ksat](md_presentations/images/soil_core.png)

--
<!-- .slide: style="text-align: left;" -->
#### SWRC (drain)
![swrc](md_presentations/images/water_retention_methods_en.png)

--
<!-- .slide: style="text-align: left;" -->
#### SWRC (samples' process)
![swrc_prep](md_presentations/images/soil_sample_preparation_en.png)

--
<!-- .slide: style="text-align: left;" -->
#### SWRC (soil hydraulic functions)
![swrc_models](md_presentations/images/retention_models_en.png)

--
<!-- .slide: style="text-align: left;" -->
#### Modeling results
![data_assim](md_presentations/images/data_assimilation_en.png)

