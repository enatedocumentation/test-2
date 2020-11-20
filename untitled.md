# 8. Integration with ABBYY FlexiCapture OCR Technology

Enate is able to provide integration with ABBYY FlexiCapture - this is achieved through use of an ABBYY FlexiCapture integrated Action \(see Builder Handbook for guidance on how to create and configure this new Action type\).

When this Action runs for any Case, documents attached to the Case can be submitted to ABBYY FlexiCapture for OCR Scanning and the processed output files will be returned and automatically attached to the Case. Which documents are submitted will depend upon whether file tagging logic is in play:

* If a file tag has been specified in the Action configuration then only files with this tag will be included in the scanning OCR activity,
* If no file tag has been specified, all files attached to the Case will be scanned and processed.

## A. On-screen User Feedback

There are various steps during the processing of an ABBYY Action in Enate. At each step, on-screen feedback informs you of what is happening. You’ll see confirmation of when the documents have successfully been submitted to ABBYY:

![](.gitbook/assets/0%20%285%29.png)

If processing completes with no issues and no manual intervention is required, you’ll see confirmation of this:

![](.gitbook/assets/1%20%288%29.png)

## B. Manually Verifying ABBYY Document

In some circumstances, documents being processed by ABBYY may require verification by a human, which can be carried out via Enate. When this is NOT required, the Enate Action will confirm successful submission of the documents to FlexiCapture on screen:

![](.gitbook/assets/2%20%286%29.png)

Additionally, a reminder text will display in next to the Action status to reaffirm that manual verification must be completed in ABBYY before continuing:

![](.gitbook/assets/3%20%286%29.png)

When you click on the green ‘Verify’ button it will open the relevant verification task in ABBYY FlexiCapture. Please note, a valid ABBYY FlexiCapture account with permissions to carry out verification in the chosen project will be required for full access.

![](.gitbook/assets/4%20%281%29.png)

Once you are logged in \(instant access will be granted if your browser is already logged into Flexicatpure\), you will be presented with ABBY FlexiCapture’s verification station screen to review and adjust information as necessary, then mark as complete:

![](.gitbook/assets/5%20%281%29.png)

## C. After Completing Manual Verification

Once you’ve finished the manual verification, the screen will confirm this has been done, but will note that there was an expection which required manual intervention:

![](.gitbook/assets/6%20%284%29.png)

## D. File Visibility after processing ABBYY Activities

Once OCR processing is complete any exported files are attached to the Case, visible in the Files section.

{% hint style="info" %}
Note: If explicit ‘Output file tags’ have been set for a given ABBYY Action \(see your administrator for how to do this\), then ABBYY will apply the output tag to all files which it processed, ready for use in downstream activities.
{% endhint %}

![](.gitbook/assets/7%20%286%29.png)

If manual verification was not required, i.e. the OCR batch processed without any human intervention, the Action will automatically close once processing is complete.

{% hint style="info" %}
Note: Only filetypes supported by ABBYY v12 onwards can be submitted. Click [here ](https://help.abbyy.com/en-us/flexicapture/12/standalone_operator/input_formats)to see the following link for list of formats supported by ABBYY. 
{% endhint %}



