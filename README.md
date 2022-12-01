<img src="https://statamic.com/assets/branding/Statamic-Logo-Rad.png" width="100" alt="Statamic Logo" />

# Fahlgren Mortine Starter Kit

This starter kit is meant to be used with the [Peak starter kit](https://statamic.com/starter-kits/studio1902/peak). When installing, you must start with peak and then install this one.

## Installation:
### Installation via the CLI
Install the statamic cli

`composer global require statamic/cli`

Create a new project with statamic-peak

`statamic new my-site studio1902/statamic-peak`

Then install the fahlgren mortine starter kit.

`php please starter-kit:install FahlgrenMortineDigital/fahlgren-statamic-starter`

### Install into an existing Statamic v3.3+ project

If you already have an existing, clean, Statamic installation you can run the following command: `php please starter-kit:install studio1902/statamic-peak`.  Follow that up then by running `php please starter-kit:install FahlgrenMortineDigital/fahlgren-statamic-starter`

## What gets added:

### Page Builder Sets
- resources/views/page_builder/_side_by_side.antlers.html

### Fieldsets
- resources/fieldsets/page_builder.yaml
- resources/fieldsets/content_tout.yaml
- resources/fieldsets/side_by_side.yaml

## Routes where examples are shown:
- `/examples` Shows an example of the different page builder components.
