 Executive Summary

This Ansible playbook (hardening.yml) is used to apply OS-level and SSH-level security hardening across all managed hosts defined in the inventory. It uses the well-established os_hardening and ssh_hardening roles, which are typically sourced from the DevSec project — a community standard for secure Linux configurations.

The playbook is executed with elevated privileges and targets all defined hosts, automating consistent security policy enforcement across the infrastructure.
