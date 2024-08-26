# Vault 🐋

This folder contains the config files for run Vault within a Docker Container.
This configuration is designed to run Vault in _Server mode_,
so that any information and configurations are persisted at every restart.
Each time the Docker container starts up, Vault will start in _Sealed mode_, allowing any operation to be performed
by undergoing an Unsealing procedure.
