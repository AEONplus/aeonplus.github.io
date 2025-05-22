---
layout: page
title: AEONlib
show_sidebar: false
menubar: software_menu
---

### AEONlib <a href="https://github.com/orgs/AEONplus/projects/3/views/1">[under development]</a>
_A set of tools for accessing observatory APIs_

#### What AEONlib is
AEONlib will provide a stand-alone Python library designed to simplify and standardized programatic access to observational resources. 
For the moment we are heavily focused on submitting observations, but retrieving data from facilities with appropiate API access is a possible direction for future development.

Features of AEONlib include:
 - **Unified Configuration** -- All facilitiy configurations, such as passwords, API keys, or authentication tokens, can be supplied via enviornment variables or a `.env` file.
 - **Standard Set of Dependencies** -- AEONlib can be installed with specific dependency groups depending on the facilities that you need.
 - **Common and Flexible Units** -- AEONlib uses astropy to convert between units. You won't need to worry about wheter a facility requires RA in dms, hms, or hour angle.
 - **Consistent Coding Conventions** -- Naming conventions and syntax will be consistent across all facilities.
 - **Shared Special Objects** -- For objects like time windows and target that are not unique to each observatory, AEONlib will provide a shared object class that can be used across multiple facilities.
 - **Robust Validation and Type Checking** -- AEONlib is type-annotated with well defined data models. This means that requests can be validated at run time, or even in the editor, rather than during submission.
 - **Up-to-date facility information** -- For properly configured Observatory APIs, updated instrument configurations can be automatically generated for AEONlib, so keeping your AEONlib version up to date helps you be confident that your observation requests remain valid through facility improvements.

#### What AEONlib is not
AEONlib is not a generic, one-size-fits-all observatory request class that will allow you to use the exact same code to submit observations to any facility. Each observatory has unique features that allow for unique and exciting science. Any generalization we could apply would inevitably either abstract out and simplify away many of those complex features, or become so complex and burdensome that it would loose any usefulness. We want all of the nuance and special capabilities of these facilities to be fully available to astronomers while simplifying and standardizing their access to them.
