function doGet(e) {
  var calculator = JSON.stringify(e);
  return HtmlService.createHtmlOutput(calculator);
//script type=”text/Javascript“
//Function calc(e)


//Form=document getElementById(“HSC form”);console
Basic=form.BasicPay.value;
Basic=parseFloat(BasicPay);
Form.DearnessAllowance.value=(Basic*0/100);
Form.HouseRentAllowance.value=(Basic*12/100);
//maximum basic = 12000
Form.MedicalAllowance.value=("500");
Form.ProvidentFund.value=("null");
Form.ProfessionalTax.value=(0)
//[If Basic >40000.value=(200), <40000.value=(150);]
Form.IncomeTax.value=(null);
Frm.Others.Value=(null);
Form.GrossSalary.value=("BasicPay+DearnessAllowance+HouseRentAllowance+MedicalAllowance")
Form.TotalDeduction.value=("ProvidentFund+ProffetionalTax+IncomeTax+Others");
Form.NetSalary.value=("GrossSalary-TotalDeduction");}
