# mixs-6-2-for-merge

MIxS: the Minimum Information about any (X) Sequence standard

# Important Notice
The 6.2 release of the MIxS repository is in transition and still has a few bugs. 

**Until we remove this message from this readme file, if you are already implementing MIxS using the 6.0 to 6.1.1 release, please continue to do so. If you are looking to download the latest usable version of MIxS, please download the artifact you need from https://github.com/GenomicsStandardsConsortium/mixs/tree/mixs6.1.1/mixs.**

If you have questions or concerns in the interm, please contact gensc-twg@groups.google.com or create an issue in this repository

## Website

[https://GenomicsStandardsConsortium.github.io/mixs-6-2-for-merge](https://GenomicsStandardsConsortium.github.io/mixs-6-2-for-merge)

## Repository Structure

* [examples/](examples/) - example data
* [project/](project/) - project files (do not edit these)
* [src/](src/) - source files (edit these)
  * [mixs_6_2_for_merge](src/mixs_6_2_for_merge)
    * [schema](src/mixs_6_2_for_merge/schema) -- LinkML schema
      (edit this)
    * [datamodel](src/mixs_6_2_for_merge/datamodel) -- generated
      Python datamodel
* [tests/](tests/) - Python tests

## Developer Documentation

<details>
Use the `make` command to generate project artefacts:

* `make all`: make everything
* `make deploy`: deploys site
</details>

## Credits

This project was made with
[linkml-project-cookiecutter](https://github.com/linkml/linkml-project-cookiecutter).
