# SIIM hackathon-images
Collection of DICOM image to compliment [SIIM's Hackathon FHIR Dataset](https://github.com/ImagingInformatics/hackathon-dataset), the images help coraborate each patient's story.

## NOTES
  * This repo is MISSING some images, which could not fit on GitHub. Those images are available on [an AWS S3 bucket](http://siim-hackathon-images.s3-website-us-east-1.amazonaws.com/) for download as ZIP files.

# Organization
Contains DICOM images (aka part 10 files) under each patient's name, nested below are folders representing the individual studies.

These files can easily be pushed in a DICOM server, e.g. Orthanc or dcm4chee, using multiple methods, one of which is the dcm4che library (not to be confused with the dcm4che*e* server).

The samples in this project span multiple specialities (both imaging and non-imaging): Radiology, Pathology, Dermatology, Radiation Therapy, Dentistry and Ophthalmology.

