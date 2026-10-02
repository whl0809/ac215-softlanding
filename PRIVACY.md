# SoftLanding Privacy Notice

Last updated: October 2026

## Overview

SoftLanding is a non-commercial educational software-development project
created for Harvard AC215.

The application helps students and interns search for short-term housing by
combining information from permitted housing-data sources.

This notice describes how SoftLanding handles information provided by users
and content retrieved from third-party sources.

## Information provided by SoftLanding users

Users may provide housing-search preferences such as:

- desired city or neighborhood
- move-in and move-out dates
- budget
- furnishing preferences
- room type
- commute preferences

This information is used to perform the requested housing search and rank
matching listings.

SoftLanding does not require Reddit credentials and does not post, comment,
vote, or send messages on behalf of users.

Search preferences are processed for the active search experience and are
not used to create advertising profiles.

## Third-party listing sources

SoftLanding may retrieve housing information from permitted APIs, datasets,
and public housing-information sources.

Each source is handled according to its own access, attribution, and
retention requirements.

Sources may include:

- university summer-housing pages
- furnished-housing providers
- public rental-market datasets
- public transit data
- the Reddit Data API, if access is approved

## Reddit Data

Reddit integration will only be enabled if Reddit approves SoftLanding's
Data API request.

If approved, SoftLanding will request read-only access to recent public
housing posts from a small number of housing-focused communities.

The application may temporarily process:

- post title
- post body
- creation time
- flair
- permalink
- author username when needed for attribution

SoftLanding does not retrieve private messages, voting activity, or unrelated
user profiles and posting histories.

Reddit results displayed by SoftLanding identify Reddit as the source and
link users to the original Reddit post.

## Automated processing

SoftLanding uses a combination of deterministic software and machine-learning
components to normalize and rank housing listings.

Processing varies by source according to the terms and data-use requirements
of that source.

Raw Reddit content is not sent to third-party AI or LLM providers.

Reddit Data is not used to train or fine-tune machine-learning models or as a
persistent model benchmark, calibration dataset, or labeled evaluation corpus.

SoftLanding does not classify Reddit users as fraudulent or infer personal
characteristics about Reddit users.

## Data retention

Application data is retained only for as long as needed to operate and
evaluate the course project.

Reddit content, if the integration is approved, is cached for no more than
48 hours and may be deleted sooner when no longer required.

Deleted or removed Reddit content is removed from SoftLanding's cached data.

Reproducible evaluation datasets are maintained separately from live-source
content.

## Data sharing

SoftLanding does not sell or license user information or third-party listing
content.

Raw Reddit content is not publicly redistributed or shared with third-party
AI providers.

Project infrastructure is hosted on Google Cloud. Access to project data is
limited to members of the SoftLanding team who require it for development
and operation.

## Security

API credentials and other secrets are stored separately from the public
source-code repository using appropriate secret-management tools.

Credentials are never committed to the public GitHub repository.

## User requests

Users may contact the project team with questions about their information or
to request deletion of information associated with their use of SoftLanding.

## Changes to this notice

SoftLanding is an early-stage course project. This notice may be updated as
the application develops. Material changes to data collection or processing
practices will be reflected here before the corresponding feature is enabled.

## Contact
SoftLanding project team  
Harvard AC215  
<haolin_wan@hms.harvard.edu>, <cindy_ren@hms.harvard.edu>, <yizhedai@hsph.harvard.edu>
