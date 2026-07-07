# Computer networks studie GPS

Status 2026-7-7:

- a bit messy
- branch gh-pages used for publishing (but imho not good practice; there are ways to publish to github pages without commiting the build outputs)
- branch main is the version corresponding to Toledo link CN-AO (but not via this ucll-networking github account, still via rafmeeusen github user) 
- branch draft_deel2 is a draft update
- by mistake draft_deel2 is currently published on https://ucll-networking.github.io/studie_gps/ (but students don't use this link yet)
- last but not least: we're in the process of deciding what to do with this content ... 


OPO: UCLL computer networks

Studie GPS: 

- studievolgorde met eerst "home networking", daarna pas de zaken die je thuis eerder niet tegenkomt
- leerdoelen uitgeschreven 

# Local setup

Debian/Ubuntu package is asciidoctor: 

`$ sudo apt install asciidoctor`

# Local usage (i.e. create html)
Linux CLI example to create html from adoc: 

`$ asciidoctor studie_gps.adoc`


