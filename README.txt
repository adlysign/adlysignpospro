ADLYSIGN POS PRO - BUILD FROM ZIP

GitHub cannot automatically extract a ZIP uploaded as a normal repository file.
Use the included workflow file at .github/workflows/build-apk-from-zip.yml in the repository.

Recommended:
1. Create an empty GitHub repository.
2. Upload adlysign-pos-pro.zip to the repository.
3. Create .github/workflows/build-apk-from-zip.yml and paste the included workflow file.
4. Open Actions > Build ADLYSIGN POS PRO APK from ZIP > Run workflow.
5. Download artifact ADLYSIGN-POS-PRO-APK.

The workflow extracts the ZIP on GitHub's server and builds the Android APK.
