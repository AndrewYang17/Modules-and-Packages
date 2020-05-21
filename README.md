# Modules-and-Packages
How to utilize __ init __.py in creating packages in python, the way of good practicing.

## Overview
- This repo is used for reference in importing modules and packages to be used across in your project.

## Problem
- I found myself was stucked and getting errors while trying to import packages around in a big complex project.
- If stick with the normal approach (write out every of the directories), the import statements seem way too long and not pretty. 
- And was trying to figure out and search around for the best pythonic convention of importing, but none of them are transparent. 

## Errors
- The errors that you most likely would be getting when playing around with importing:
1. ValueError: attempted relative import beyond top-level package
2. ImportError: attempted relative import with no known parent package
