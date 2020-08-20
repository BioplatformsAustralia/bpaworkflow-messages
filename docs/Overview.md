# Overview of bpaworkflow and bpa-ingest error messages

## Informative

| Code | Message | Source Link |
| ---- | ------- | -----|
| E1000 | All is good ||

## File

| Code | Message | Source Link |
| ---- | ------- | -----|
| [E2000](E2000.md) | No match for filename | [abstract.py](https://github.com/BioplatformsAustralia/bpa-ingest/blob/master/abstract.py#L37) |
| [E2001](E2001.md) | File does not meet convention | [validate.py](https://github.com/BioplatformsAustralia/bpaworkflow/blob/master/validate.py#L63) |

## Metadata

| Code | Message | Source Link |
| ---- | ------- | -----|
| E3000 | Invalid sample_extraction_id | [utils.py](https://github.com/BioplatformsAustralia/bpa-ingest/blob/master/ingest_utils.py#L45) |
| [E3001](E3001.md) | Missing column in submission sheet | [wrapper.py](https://github.com/BioplatformsAustralia/bpa-ingest/blob/master/excel_wrapper.py#L177) |
| [E3002](E3002.md) | Column not mapped in submission sheet | [wrapper.py](https://github.com/BioplatformsAustralia/bpa-ingest/blob/master/excel_wrapper.py#L190) |
| [E3003](E3003.md) | The provided spreadsheet could not be read | [validate.py](https://github.com/BioplatformsAustralia/bpaworkflow/blob/master/validate.py#L53)  |

## Data

| Code | Message | Source Link |
| ---- | ------- | -----|
| E4000 | PCR Value | [utils.py](https://github.com/BioplatformsAustralia/bpa-ingest/blob/master/ingest_utils.py#L22) |
| [E4001](E4001.md) | [tasks.py](Problem capturing packages and resources | https://github.com/BioplatformsAustralia/bpaworkflow/blob/master/tasks.py#L218) |


## System

| Code | Message | Source Link |
| ---- | ------- | -----|
| E9000 | HTTP transfer error | [fetch_data.py](https://github.com/BioplatformsAustralia/bpa-ingest/blob/master/fetch_data.py#L106) |
