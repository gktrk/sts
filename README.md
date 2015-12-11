# sts
NIST Statistical Test Suite

Official Website: http://csrc.nist.gov/groups/ST/toolkit/rng/documentation_software.html

This repo does not include the example data files. I made slight adjustments so that I can
run multiple instances of sts in parallel.

 * Takes an optional argument [output dir]. The directory must be populated using
   create-dir-script prior to the run. Useful for running multiple assess processes
   in parallel without their outputs clobbering.
 * Input file name "-" reads data from stdin. Useful with UNIX pipes, popen etc.
