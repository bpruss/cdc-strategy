# Current Projects List

## Website Projects

### cloud-data-consulting-site
- [ ] Connect to Hubspot forms to capture contact info from website and future landing pages
- [ ] Massively expand and make more impressive the site in general
  - Use prompts in the prompts folder
  - Use wireframe information from wireframe folder (AI site wireframes)
- [ ] Research assessment frameworks for AI readiness conversation/services
  - Recall one that was very complete from former client
  - Survey of many "facets" of business and data readiness and organizational readiness
  - Use as inspiration for AI readiness conversation for services
- [ ] Add updated use cases from existing clients
- [ ] Create use case for Aubuchon
  - Most recent: report to help store managers staff appropriately based on sales and predicted sales and profits and predicted profits
  - Pull together all the things we can do for Aubuchon

### BerniePruss.com
- [ ] Port to new tech stack (new project)
- [ ] Stop paying for Craig and his hosting company ASAP

## Development Projects

### cdc-ai
**Big project - need to figure out where to start and sequence**
- [ ] Plan project sequence and starting point
- [ ] Set up simple web framework (need to determine which web tool)
- [ ] Database connectivity to Snowflake
  - Start with CDC PRD and dev database there (perhaps the ODS)
- [ ] Connectivity to AWS - determine which account to put data in
- [ ] Verify shared code is working appropriately
- [ ] Look at merging cloud-data-consulting-site/shared into cdc-shared submodule

## Infrastructure & Operations

### AWS Cleanup
- [ ] Migrate domains from legacy account to CDC account
- [ ] Migrate S3 buckets from legacy account to CDC account

## Personal - Dad's Funeral Related
- [ ] Work on obituary
- [ ] Create playlist
- [ ] Find photos and put them into a video

## Personal - Other
- [ ] Take laptop to Apple to get space bar fixed

## Repository Organization

### GitHub Repos Folder on MacMini
- [ ] Review and organize github repos folder on macmini
- [ ] Extract important items (e.g., Erwin data models) to consolidate into cdc-reference repo
- [ ] Clean up duplicates similar to yesterday's work but handle additional projects

### Repository Structure Improvements
- [ ] Consider shortening cloud-data-consulting-site to cdc-site or site-cdc
- [ ] Consider renaming berniepruss.com to site-bfp (initials)
- [ ] Remove submodules from local storage since most are submodules in parent projects
- [ ] Establish decision log update process for multiple developers
  - How to avoid duplicate decision numbers
  - PR process for review and approval

## Snowflake & Infrastructure

### Snowflake-account-provisioning Enhancements
- [ ] Move snowflake-sql-libraries into a submodule and setup for deployment
- [ ] Add option for RAW_ prefix in raw database names
  - Make RAW_ first so they sort together OR second for existing deployment compatibility
- [ ] Add feature to sync Snowflake account drift back into Terraform control
- [ ] Identify features/methods to move to cdc-shared
  - Snowflake connection methods
  - Snowsql methods
  - Terraform methods
  - Python methods
  - Consider writing article about this

### cdc-ai Architecture & Data Strategy
- [ ] Architect large file systems integration with Snowflake/AWS
- [ ] Research Snowflake capabilities for large files
- [ ] Consider AWS security integration setup
- [ ] Design external Snowflake stages pointing to AWS S3 buckets
- [ ] Determine data flow: push to AWS vs push to Snowflake → external stage/S3
- [ ] Research S3 compression options without losing utility/ease of use
- [ ] Plan simple POC (proof of concept)
- [ ] Plan POV (proof of value)

## Product Ideas

### File Management & Mining System
- [ ] Design system to index, dedupe, and mine old files for important information
- [ ] Handle legacy AWS S3 files
- [ ] Handle old Windows machine files
- [ ] Research indexing solutions (previously used paid indexing program)
- [ ] Consider integration with cdc-ai for this capability

---

*Continue adding items below as needed...*
