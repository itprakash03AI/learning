# QueryStudio -- UAT deployment

**Deploy `Deployment_2026_11_13_8553b5e9f.zip`.** Read `DEPLOYMENT_2026_11_13_UAT.html` first. Main fix: AWS S3 connections that kept dropping.

| File | What it is |
|---|---|
| `Deployment_2026_11_13_8553b5e9f.zip` | The package: every change since the deployed 2026-11-12 package (9c086f618) -- 55 files |
| `Deployment_2026_11_13_8553b5e9f.PARTS.txt` | Its sha256 -- check it before deploying |
| `DEPLOYMENT_2026_11_13_UAT.html` | The deploy guide: what is in it, start-up database changes, order, images, Helm, what to test, rollback |
| `Charts_2026_11_12_7640e4a34.zip` | The charts (unchanged): `./deploy.sh uat`; Spark Connect is off on UAT |
| `SPARK_AND_QUERY_PODS_TEST_GUIDE_2026_11_11.html` | How to test Spark pods and query pods on UAT |

## Architecture

| File | What it is |
|---|---|
| `Architecture_2026_11_12.zip` | All four in one file (for networks that block .pptx / .html downloads): the 18-slide architect deck `ARCHITECTURE_FLOW_2026_11_12.pptx` + `.pdf`, and How QueryStudio works `ARCHITECTURE_2026_11_10.html` + `.pdf` |
| `ARCHITECTURE_2026_11_10.pdf` | How QueryStudio works (opens anywhere) |
| `ARCHITECTURE_2026_11_10.html` | The same as a web page (download it; GitHub shows .html as code) |
| `ARCHITECTURE_FLOW_2026_11_12.pptx` / `.pdf` | The 18-slide architect deck |
