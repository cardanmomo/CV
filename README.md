# Curriculum Vitae

See latest master on [moramoreno.com/cv](https://moramoreno.com/cv/)

* Based on [resume](https://github.com/chmduquesne/resume) by Christophe-Marie Duquesne.
* Modified to fit my needs

## To use:

* Update `metadata.yaml`.
* Run `make`.
* It is possible that some of the html beautifying tricks found in `scripts/modify_html.sh` have to be partly rewritten.
* For pdf generation:
    - install puppeteer with `nvm`:
        - `cd puppeteer`
        - `npm i puppeteer`
        - `cd ../`
    - For problems with a sandbox you can run (as root)
        - `echo 1 > /proc/sys/kernel/unprivileged_userns_clone`
