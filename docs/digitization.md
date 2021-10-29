# Digitization with DT Atom

---

# Capture One Online User Guides

[Capture One 21](https://support.captureone.com/hc/en-us/categories/360000279017-User-Guide)

[Capture One CH](https://support.captureone.com/hc/en-us/sections/360000704038-Capture-One-Cultural-Heritage-CH-)

# Transmissive (Film)

[Digital Transitions Digitization Workflow Guide: Transmissive](/assets/DTCH_DigitizationWorkflows_Transmissive_2018.pdf)

## Transmissive Preflight Steps

1. Select lens and extension tubes (See [Lens/Resolution Chart](#lensresolution-chart))
2. Set camera position, focus and, level
3. Set aperture to ƒ/10
4. Set Mode, Profile, and Curve
    - **Mode:** Photography
    - **ICC Profile:** Flat Art Reproduction LED DT Photon
    - **Curve:** Linear Scientific
5. Capture LCC raw file
6. Generate LCC profile
7. Set white balance based on light source
8. Set exposure base on light source
    - Adjust shutter speed until the brightest luminance value of the LAB Color Readouts is as close to 98, without going over, as possible.


## Lens/Resolution Chart

|Film Format |Lens |Extension Tubes|Resolution|
|------------|-----|---------------|----------|
|8×10\"      |72mm |None           |~1300 ppi |
|5×7\"       |72mm |None           |~2100 ppi |
|4×5\"       |120mm|None           |~2600 ppi |
|6×7         |120mm|40mm           |~4500 ppi |
|6×6         |120mm|40mm           |~4500 ppi |
|645         |120mm|60mm           |~6000 ppi |
|35mm        |120mm|120mm          |~9900 ppi |



# Reflective (Flat Artwork)

[Digital Transitions Digitization Workflow Guide: Reflective](/assets/DTCH_DigitizationWorkflows_Reflective_2018.pdf)

## Reflective Preflight Steps
1. Select 72mm lens
2. Set aperture to ƒ/8
3. Set camera position, focus, and level
4. Set Mode, Profile, and Curve
    - **Mode:** Photography
    - **ICC Profile:** ColorChecker SG
    - **Curve:** Linear Scientific
5. Capture LCC raw file
6. Generate LCC profile
7. Set exposure based on patch G5 on ColorChecker SG.
    - The ColorChecker SG target patch G5 should have a Luminance value of 65.1 without exceeding it.
8. Set white balance based on patch F5 on ColorChecker SG
9. After captures are complete use the [DT Adobe RGB overlay](/assets/DTDCH_Overlays_ColorCheckerSG_Adobe1998.png) to fine tune exposure using levels. Apply levels to all captures.
10. Use [Delt.ae](https://deltae.picturae.com) to verify color accuracy.
    - Export a full size jpg in Adobe 1998 RGB and upload for validation.
