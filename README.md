# KBAstroUtils

This is a collection of modules for analyses related to astrophysics by Dr. Kornpob Bhirombhakdi. Contact: kbhirombhakdi@stsci.edu

Tasks include:

    - dqmask.py = handle data quality (DQ) arrays
    
    - container.py = handle declaring attibutes given keys and values
    
    - segmentation.py = wrapper for making a segmentation map (used to be source.py in version < 1.2.0)
    
    - sub2full.py = mapping a subarray image back to its full frame
    
    - gnd.py = wrapper, and main class for grism reduction
    
    - grismconf.py = read conf file for grism reduction
    
    - grismsens.py = read sens file for grism reduction
    
Known issues:

    - ???

v.2.0.0a

    - New APIs: gnd.py
    
    - Implement: grismapcorr.py, make_sip.py
    
---

v.1.3.1

    - Fix import

v.1.3.0

    - Implement: grismconf.py, gnd.py, grismsens.py
    
v.1.2.0

    - Implement: sub2full.py

    - Change: source.py to segmentation.py
    
    - Fix description: segmentation.py

v.1.1.0

    - Implement: container.py, source.py
    
    - Fix description: dqmask.py
    
v.1.0.2

    - Fix description of dqmask.py
    
v.1.0.1

    - Fix import modules in dqmask.py
    
v.1.0.0

    - Implement dqmask.py
    