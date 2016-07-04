# cmsdist
CMS Offline Software build configuration

Main task:
Porting Data & Workflow Management code to python 3

Supervisors: Eric Vaandering, Dirk Hufnagel

Description: The WMAgent and Tier0 are responsible for submitting and managing tens of
thousands or processing jobs on the Worldwide LHC Computing Grid. DAS and DBS are responsible
for tracking data and meta-data of PB of files. This code is in production based on python 2.7. The
candidate will work with the development teams to prepare this code for python 3.x, beginning with
an audit of the suitability of the external software used and identifying replacements where needed.
Automated tools will also be employed to help with this porting.

1st Week:
1. Create README.md -done 
2. Create dependencies graph(tree) to check if libraries are suported by python3+ -done
https://github.com/dmwm/ 
3. Read Cheetah and jinja2 syntax
4. Create a scrip to automaticaly conver Cheetah to jinja2 templates
5.DAS templates and test conversion
