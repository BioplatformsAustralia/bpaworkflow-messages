# Overview of bpaworkflow and bpa-ingest error messages

## Informative

| Code | Message | Link |
| ---- | ------- | -----|
| E1000 | All is good ||

## File

| Code | Message | Link |
| ---- | ------- | -----|
| [E2000](E2000.md) | No match for filename | https://github.com/BioplatformsAustralia/bpa-ingest/blob/a212eb233ef384e6f7c331791a01471540bdefa9/bpaingest/abstract.py#L37 |
| [E2001](E2001.md) | File does not meet convention | https://github.com/BioplatformsAustralia/bpaworkflow/blob/60c6d4546d2fe1b4d80927493a0305feb10c3073/bpaworkflow/bpaworkflow/validate.py#L63 |

## Metadata

| Code | Message | Link |
| ---- | ------- | -----|
| E3000 | Invalid sample_extraction_id | https://github.com/BioplatformsAustralia/bpa-ingest/blob/40e8436f0d19316fb2cd0b0d626df55d90cd8346/bpaingest/libs/ingest_utils.py#L45 |
| [E3001](E3001.md) | Missing column in submission sheet | https://github.com/BioplatformsAustralia/bpa-ingest/blob/a212eb233ef384e6f7c331791a01471540bdefa9/bpaingest/libs/excel_wrapper.py#L177 |
| [E3002](E3002.md) | Column not mapped in submission sheet | https://github.com/BioplatformsAustralia/bpa-ingest/blob/a212eb233ef384e6f7c331791a01471540bdefa9/bpaingest/libs/excel_wrapper.py#L190 |
| [E3003](E3003.md) | The provided spreadsheet could not be read | https://github.com/BioplatformsAustralia/bpaworkflow/blob/60c6d4546d2fe1b4d80927493a0305feb10c3073/bpaworkflow/bpaworkflow/validate.py#L53  |

## Data

| Code | Message | Link |
| ---- | ------- | -----|
| E4000 | PCR Value | https://github.com/BioplatformsAustralia/bpa-ingest/blob/40e8436f0d19316fb2cd0b0d626df55d90cd8346/bpaingest/libs/ingest_utils.py#L22 |
| [E4001](E4001.md) | Problem capturing packages and resources | https://github.com/BioplatformsAustralia/bpaworkflow/blob/60c6d4546d2fe1b4d80927493a0305feb10c3073/bpaworkflow/bpaworkflow/tasks.py#L218 |


## System

| Code | Message | Link |
| ---- | ------- | -----|
| E9000 | HTTP transfer error | https://github.com/BioplatformsAustralia/bpa-ingest/blob/df2c20463079e344d999e3d79090c40d9b613ca5/bpaingest/libs/fetch_data.py#L106 |
