cython_setup_template
=====================

Template for setup.py file that provides 

1. 'cleanall' rule to remove cython generated files
2. enforces using --inplace flag to build_ext
3. only builds x86_64 executables.
