# simple-scripts
# A small set of simple scripts.
#

# Wraps a command in a flock call to ensure multiple instances do not run
flock_nb /path/to/lock.file command to run
