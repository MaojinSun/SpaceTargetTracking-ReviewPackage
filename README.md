# Space Target Tracking Review Package

This repository provides the executable review package associated with the
paper "High-Dynamic Space Target Tracking under Time-Varying
Visual Delay Using a Spaceborne Gimbal."

## Download

Download `SpaceTargetTracking_ReviewPackage_V1.0.zip` from the
[V1.0 release](../../releases/tag/V1.0). Verify the archive against the digest
in `SHA256SUMS.txt` before use.

The package contains four executable demonstrations:

1. visual delay identification and current LOS-state reconstruction (Fig. 5);
2. multirate platform and gimbal coordination (Fig. 8);
3. ASMO disturbance estimation and rejection;
4. integrated noncoplanar rendezvous tracking.

The executable demonstrations reproduce representative time-domain results.
Multi-seed statistics and parameter sweeps are not included.

## Requirements

- Windows 10 or Windows 11, 64 bit;
- MATLAB Runtime R2024b, available without a MATLAB license;
- an access credential for first activation.

## Access

Editors and reviewers receive the access credential separately through the
manuscript submission system. Researchers may request a credential for
noncommercial academic evaluation from the corresponding author:

Zichen Zhao  
Email: bitzhaozc@foxmail.com

Credentials are issued for individual evaluation and must not be disclosed or
redistributed. The local access period is 365 days from first activation.

## Use

After extracting the archive, read its `README.md` and double-click the batch
file for the required demonstration. The default parameters reproduce the
corresponding reference cases. Parameters listed in `PARAMETERS.md` may be
adjusted within their specified ranges. Each run records the effective
configuration and SHA-256 provenance information with the numerical results.

Use of the package is governed by `LICENSE.txt`. The package is available for
authorized, noncommercial academic evaluation and is not open-source software.
