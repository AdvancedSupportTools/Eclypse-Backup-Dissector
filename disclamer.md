═══════════════════════════════════════════════════════════════════════════════
                         ECLYPSE BACKUP DISSECTOR
                              IMPORTANT DISCLAIMER
═══════════════════════════════════════════════════════════════════════════════

                    READ THIS CAREFULLY BEFORE USING THIS SOFTWARE

═══════════════════════════════════════════════════════════════════════════════

THIS IS A COMMUNITY TOOL – NOT AN OFFICIAL DISTECH CONTROLS PRODUCT

This application ("Eclypse Backup Dissector") is a special utility developed by
members of the Distech Controls Advanced Support Team and is NOT a sanctioned,
endorsed, or official product release by Distech Controls Inc. or any of its
affiliates.

═══════════════════════════════════════════════════════════════════════════════
1. PROJECT STATUS AND NATURE
═══════════════════════════════════════════════════════════════════════════════

✓ INDEPENDENTLY DEVELOPED
  This tool was developed independently to assist with analysis and extraction
  of ECLYPSE controller backup ZIP files for troubleshooting and support
  purposes.

✓ NO PROPRIETARY TECHNOLOGY
  This tool does NOT rely on, embed, or access any proprietary Distech Controls
  internal systems, confidential tooling, or unpublished protocols. It operates
  entirely on file-based backups using standard ZIP and JSON processing.

✓ READ‑ONLY BY DESIGN (SOURCE DATA)
  The tool does NOT modify controller firmware, live systems, or backup ZIP
  contents unless explicitly extracting files to a local workspace chosen by
  the user.

✓ COMMUNITY DISTRIBUTION
  This utility may be shared freely within the Distech Controls partner and
  integrator community.

✗ SOURCE CODE NOT OFFICIALLY PUBLISHED
  While written as a standalone utility, this project is not distributed as an
  official open-source release unless otherwise stated by the authors.

✓ DISCRETIONARY SUPPORT
  Informal support may be provided by members of the Advanced Support Team at
  their sole discretion, primarily for:
    • Authorized Distech Controls System Integrators (SIs)
    • Authorized Distributors
    • OEM Partners
    • Distech Controls internal engineering or support teams

═══════════════════════════════════════════════════════════════════════════════
2. WARRANTY DISCLAIMER
═══════════════════════════════════════════════════════════════════════════════

THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT.

IN NO EVENT SHALL DISTECH CONTROLS INC., ITS AFFILIATES, OR THE AUTHORS OF THIS
SOFTWARE BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN
ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

═══════════════════════════════════════════════════════════════════════════════
3. NOT COVERED BY DISTECH CONTROLS SUPPORT
═══════════════════════════════════════════════════════════════════════════════

✗ This tool is NOT covered by any Distech Controls product warranty
✗ This tool is NOT covered by standard Distech Controls support agreements
✗ This tool is NOT subject to formal Distech Controls QA or validation processes
✗ This tool is NOT part of official Distech product release cycles
✗ This tool is NOT maintained under any service level agreement (SLA)

Any assistance provided is informal, best‑effort, and may be withdrawn at any
time without notice.

═══════════════════════════════════════════════════════════════════════════════
4. USE AT YOUR OWN RISK
═══════════════════════════════════════════════════════════════════════════════

Although this tool has been tested internally for common support scenarios, it
has NOT undergone the full verification, certification, or regression testing
required for official Distech Controls software products.

Users assume all risks associated with:
  • Use of extracted configuration and backup data
  • Interpretation of configuration reports
  • Handling of sensitive or security-related information
  • Workspace and file system changes on the local machine
  • Integration into internal troubleshooting workflows
  • Data handling, retention, and security practices

═══════════════════════════════════════════════════════════════════════════════
5. WHAT THIS TOOL IS NOT
═══════════════════════════════════════════════════════════════════════════════

This tool is NOT:
  ✗ An official Distech Controls software product
  ✗ Required for normal operation of ECLYPSE controllers
  ✗ A replacement for official Distech commissioning or service tools
  ✗ Certified or validated by Distech Controls product management
  ✗ Supported under Distech Controls maintenance agreements
  ✗ A commitment by Distech Controls to long‑term development or updates

═══════════════════════════════════════════════════════════════════════════════
6. INTENDED USERS
═══════════════════════════════════════════════════════════════════════════════

This utility is intended for use by experienced technical professionals,
including:
  • Advanced system integrators
  • Technical support engineers
  • Field service specialists
  • Engineering and QA personnel
  • IT professionals supporting BAS environments

Users are expected to understand:
  • ECLYPSE controller backup structures
  • JSON-based configuration data
  • Network, security, and protocol concepts
  • Risks associated with handling configuration and credential data
  • Safe handling of customer backup files

═══════════════════════════════════════════════════════════════════════════════
7. SUPPORT AND ASSISTANCE
═══════════════════════════════════════════════════════════════════════════════

LIMITED SUPPORT AVAILABILITY:
Support is provided informally and at the discretion of the tool’s authors or
Advanced Support Team members.

Support avenues may include:
  • GitHub Issues (if applicable)
  • Direct communication with the maintainer
  • Internal Distech Controls collaboration channels

NO GUARANTEES:
  • No guaranteed response times
  • No SLA or escalation path
  • No obligation for bug fixes or enhancements
  • Development may stop without notice

═══════════════════════════════════════════════════════════════════════════════
8. ACKNOWLEDGMENT AND ACCEPTANCE
═══════════════════════════════════════════════════════════════════════════════

BY USING THIS SOFTWARE, YOU ACKNOWLEDGE AND AGREE THAT:

1. You have read and understood this disclaimer in full
2. You understand this is NOT an official Distech Controls product
3. You accept that no warranty or guarantee is provided
4. You assume all responsibility for use and outcomes
5. You will not hold Distech Controls Inc. or the authors liable
6. You understand support is discretionary and may not be available
7. You will evaluate suitability before use in production environments
8. You will protect any sensitive data contained in extracted backups

═══════════════════════════════════════════════════════════════════════════════
9. LIMITATION OF LIABILITY
═══════════════════════════════════════════════════════════════════════════════

TO THE MAXIMUM EXTENT PERMITTED BY LAW, IN NO EVENT SHALL DISTECH CONTROLS INC.,
ITS AFFILIATES, EMPLOYEES, OR THE AUTHORS OF THIS SOFTWARE BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, OR CONSEQUENTIAL DAMAGES, INCLUDING BUT
NOT LIMITED TO LOSS OF DATA, LOSS OF PROFITS, BUSINESS INTERRUPTION, OR SECURITY
INCIDENTS ARISING FROM USE OF THIS SOFTWARE.

═══════════════════════════════════════════════════════════════════════════════
10. LICENSING
═══════════════════════════════════════════════════════════════════════════════

Unless otherwise stated, this tool is provided without an explicit commercial
license and may include third‑party components governed by their respective
licenses.

Users are responsible for ensuring compliance with all applicable licensing
terms.

═══════════════════════════════════════════════════════════════════════════════
11. QUESTIONS OR CONCERNS
═══════════════════════════════════════════════════════════════════════════════

Questions regarding this disclaimer or the nature of this tool should be
directed to the project maintainer or discussed via the community channel
where the tool was obtained.

For official Distech Controls product support, contact Distech Controls through
official support channels only.

═══════════════════════════════════════════════════════════════════════════════

Document Version: 1.0
Last Updated: April 22, 2026
Application Name: Eclypse Backup Dissector
Applicable Tool Version: v1.3.3

═══════════════════════════════════════════════════════════════════════════════
