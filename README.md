# SANS Course Indexes

## Setup Instructions

This guide will walk you through the initial setup required to start working with this repository.

### Step 1: Update Package List

First, update your package list to ensure you have access to the latest versions:

```bash
sudo apt update
```

### Step 2: Install Git

Install Git, a version control system for tracking changes in source code:

```bash
sudo apt install git
```

### Step 3: Configure Git

Set up your Git user information. Replace `Mona Lisa` with your name and `user@example.com` with your email address:

```bash
git config --global user.name "Mona Lisa"
git config --global user.email "user@example.com"
```

### Step 4: Install TeX Live

Install texlive for working with TeX/LaTeX documents:

* Install the TexLive base 

```
sudo apt-get install texlive-latex-base
```

* Also install the recommended and extra fonts to avoid running into the error [1], when trying to use pdflatex on latex files with more fonts.

```
sudo apt-get install texlive-fonts-recommended
sudo apt-get install texlive-fonts-extra
```


* Install the extra packages,

```
sudo apt-get install texlive-latex-extra
```

### Step 5: Clone the repo

```bash
git clone <repo-url>
```

### Step 5: Build the Index for 508

To build the index for 401, run:

```bash
./make.sh 401
```

## Connecting to GitHub

To connect this repository with GitHub, follow these steps:

### Step 1: Access GitHub Developer Settings

Navigate to your GitHub account settings:

- Go to **Settings**
- Select **Developer settings**
- Click on **Personal access tokens**
- Choose **Fine-grained tokens**
- Click **Generate new token**

### Step 2: Use Access Token

The generated access token will be used as your password when prompted in the command line during operations that require GitHub authentication.

---

**Note:** Always keep your access token secure and never share it in your code or public repositories.

---

**Stuff to index**

- Important terms
- Configurations
- Tools
- Commands


| Badge | Course | Certification | Index |
| -- | -- | -- | -- |
| ![GREM](https://www.giac.org/images/design/custom/icons/certs/small/grem-gold.png) | FOR610 | GIAC Reverse Engineering Malware (GREM) | [Index](https://github.com/ancailliau/sans-indexes/blob/main/index-610.pdf) |
| ![GCFA](https://www.giac.org/images/design/custom/icons/certs/small/gcfa-gold.png) | FOR508 | GIAC Certified Forensic Analyst (GCFA) | [Index](https://github.com/ancailliau/sans-indexes/blob/main/index-508.pdf) |
| ![GCTI](https://www.giac.org/images/design/custom/icons/certs/small/gcti-gold.png) | FOR578 | GIAC Cyber Threat Intelligence (GCTI) | [Index](https://github.com/ancailliau/sans-indexes/blob/main/index-578.pdf) |
| ![GSEC](https://www.giac.org/images/design/custom/icons/certs/small/gsec-gold.png) | SEC401 | GIAC Security Essentials (GSEC) | [Index](https://github.com/ancailliau/sans-indexes/blob/main/index-401.pdf) |
| ![GCIH](https://www.giac.org/images/design/custom/icons/certs/small/gcih-gold.png) | SEC504 | GIAC Certified Incident Handler (GCIH) | [Index](https://github.com/ancailliau/sans-indexes/blob/main/index-504.pdf) |
| ![GDAT](https://www.giac.org/images/design/custom/icons/certs/small/gdat-gold.png) | SEC599 | GIAC Defending Advanced Threats (GDAT) | [Index](https://github.com/ancailliau/sans-indexes/blob/main/index-599.pdf) |

You can find many other indexes on the [repository of the original template](https://github.com/dhondta/tex-course-index-template/), e.g.

* [GIAC Systems and Network Auditor (GSNA)](https://github.com/dhondta/tex-course-index-template/blob/master/examples/sans/aud507.pdf)
* [GIAC Certified Enterprise Defender (GCED)](https://github.com/dhondta/tex-course-index-template/blob/master/examples/sans/sec501.pdf)
* [GIAC Certified Windows Security Administrator (GCWN)](https://github.com/dhondta/tex-course-index-template/blob/master/examples/sans/sec505.pdf)
* [GIAC Web Application Penetration Tester (GWAPT)](https://github.com/dhondta/tex-course-index-template/blob/master/examples/sans/sec542.pdf)
* [GIAC Penetration Tester (GPEN)](https://github.com/dhondta/tex-course-index-template/blob/master/examples/sans/sec560.pdf)
* [GIAC Critical Controls Certification (GCCC)](https://github.com/dhondta/tex-course-index-template/blob/master/examples/sans/sec566.pdf)
* [GIAC Mobile Device Security Analyst (GMOB)](https://github.com/dhondta/tex-course-index-template/blob/master/examples/sans/sec575.pdf)
