# ReklamStore-DSP-Conversion-Pixel
ReklamStore DSP Conversion Pixel GTM Template

## <a id="installation"></a>Installation

1. Download the `template.tpl` file

2. Create a new tag template in the Templates menu
    ![templates_menu](./images/firstImage.png)
    
3. Import the `template.tpl` file
    ![import_template](./images/template_import.png)
    
4. Save Template
    ![import_template](./images/saveTemplate.png)
    
5. Create new price Variable
    ![import_template](./images/createVariable.png)
   
6. Add variable name and select  variable configuration.(<b>Note:
In the example here, variables are constant.
If you have dynamic variable , use the data layer variable.So you can use dynamic data as a variable.</b>)
    ![import_template](./images/newPriceVariable.png)
    
7. Select Constant in Utilities
    ![import_template](./images/constant.png)

8. Enter price variable value and save your price value.
    ![import_template](./images/saveVariable.png)

9. Create the clickId variable by following the same steps as the price variable<b>(ref:5-8)</b>.

10. Create a new Tag.
    ![import_template](./images/newTag.png)

11. Enter a tag name and Select tag type in Custom.
    ![import_template](./images/selectTag.png)

12. Select price and clickId variables for new Tag.
    ![import_template](./images/selectVariable.png)
    
13. Select price Variable.
     ![import_template](./images/selectPriceVariable.png)

14. Select the clickId variable by following the same steps as the price variable<b>(ref:12-13)</b>.

15. Create new trigger for your tag.
    ![import_template](./images/newTrig.png)
    
16. Select plus sign.
    ![import_template](./images/newTrigger.png)

17. Enter trigger name and select trigger configuration
    ![import_template](./images/createTrigger.png)

18. Select Page View.
    ![import_template](./images/selectPageView.png)

19. Set the page where Trigger will fires on and save trigger.
    ![import_template](./images/editTrigger.png)

20. Save tag and <b>Submit<b> workspace changes.
    ![import_template](./images/saveTag.png)
