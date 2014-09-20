<font color=black> <script language="JavaScript">
function calculate1()
{
   seq = parseFloat(document.theForm.seq.value);
   if (seq == 96) doe96();
   if (seq == 24) doe24();
}
function doe96()
{
   res1 = new Array (.001, .00102, .00105, .00107, .0011, .00113, .00115, .00118, .00121, .00124, .00127, .0013, .00133, .00137, .0014, .00143, .00147, .0015, .00154, .00158, .00162, .00165, .00169, .00174, .00178, .00182, .00187, .00191, .00196, .002, .00205, .0021, .00215, .00221, .00226, .00232, .00237, .00243, .00249, .00255, .00261, .00267, .00274, .0028, .00287, .00294, .00301, .00309, .00316, .00324, .00332, .0034, .00348, .00357, .00365, .00374, .00383, .00392, .00402, .00412, .00422, .00432, .00442, .00453, .00464, .00475, .00487, .00499, .00511, .00523, .00536, .00549, .00562, .00576, .0059, .00604, .00619, .00634, .00649, .00665, .00681, .00698, .00715, .00732, .0075, .00768, .00787, .00806, .00825, .00845, .00866, .00887, .00909, .00931, .00953, .00976, .01, .0102, .0105, .0107, .011, .0113, .0115, .0118, .0121, .0124, .0127, .013, .0133, .0137, .014, .0143, .0147, .015, .0154, .0158, .0162, .0165, .0169, .0174, .0178, .0182, .0187, .0191, .0196, .02, .0205, .021, .0215, .0221, .0226, .0232, .0237, .0243, .0249, .0255, .0261, .0267, .0274, .028, .0287, .0294, .0301, .0309, .0316, .0324, .0332, .034, .0348, .0357, .0365, .0374, .0383, .0392, .0402, .0412, .0422, .0432, .0442, .0453, .0464, .0475, .0487, .0499, .0511, .0523, .0536, .0549, .0562, .0576, .059, .0604, .0619, .0634, .0649, .0665, .0681, .0698, .0715, .0732, .075, .0768, .0787, .0806, .0825, .0845, .0866, .0887, .0909, .0931, .0953, .0976, .1, .102, .105, .107, .11, .113, .115, .118, .121, .124, .127, .13, .133, .137, .14, .143, .147, .15, .154, .158, .162, .165, .169, .174, .178, .182, .187, .191, .196, .2, .205, .21, .215, .221, .226, .232, .237, .243, .249, .255, .261, .267, .274, .28, .287, .294, .301, .309, .316, .324, .332, .34, .348, .357, .365, .374, .383, .392, .402, .412, .422, .432, .442, .453, .464, .475, .487, .499, .511, .523, .536, .549, .562, .576, .59, .604, .619, .634, .649, .665, .681, .698, .715, .732, .75, .768, .787, .806, .825, .845, .866, .887, .909, .931, .953, .976, 1, 1.02, 1.05, 1.07, 1.1, 1.13, 1.15, 1.18, 1.21, 1.24, 1.27, 1.3, 1.33, 1.37, 1.4, 1.43, 1.47, 1.5, 1.54, 1.58, 1.62, 1.65, 1.69, 1.74, 1.78, 1.82, 1.87, 1.91, 1.96, 2, 2.05, 2.1, 2.15, 2.21, 2.26, 2.32, 2.37, 2.43, 2.49, 2.55, 2.61, 2.67, 2.74, 2.8, 2.87, 2.94, 3.01, 3.09, 3.16, 3.24, 3.32, 3.4, 3.48, 3.57, 3.65, 3.74, 3.83, 3.92, 4.02, 4.12, 4.22, 4.32, 4.42, 4.53, 4.64, 4.75, 4.87, 4.99, 5.11, 5.23, 5.36, 5.49, 5.62, 5.76, 5.9, 6.04, 6.19, 6.34, 6.49, 6.65, 6.81, 6.98, 7.15, 7.32, 7.5, 7.68, 7.87, 8.06, 8.25, 8.45, 8.66, 8.87, 9.09, 9.31, 9.53, 9.76, 10, 10.2, 10.5, 10.7, 11, 11.3, 11.5, 11.8, 12.1, 12.4, 12.7, 13, 13.3, 13.7, 14, 14.3, 14.7, 15, 15.4, 15.8, 16.2, 16.5, 16.9, 17.4, 17.8, 18.2, 18.7, 19.1, 19.6, 20, 20.5, 21, 21.5, 22.1, 22.6, 23.2, 23.7, 24.3, 24.9, 25.5, 26.1, 26.7, 27.4, 28, 28.7, 29.4, 30.1, 30.9, 31.6, 32.4, 33.2, 34, 34.8, 35.7, 36.5, 37.4, 38.3, 39.2, 40.2, 41.2, 42.2, 43.2, 44.2, 45.3, 46.4, 47.5, 48.7, 49.9, 51.1, 52.3, 53.6, 54.9, 56.2, 57.6, 59, 60.4, 61.9, 63.4, 64.9, 66.5, 68.1, 69.8, 71.5, 73.2, 75, 76.8, 78.7, 80.6, 82.5, 84.5, 86.6, 88.7, 90.9, 93.1, 95.3, 97.6, 100, 102, 105, 107, 110, 113, 115, 118, 121, 124, 127, 130, 133, 137, 140, 143, 147, 150, 154, 158, 162, 165, 169, 174, 178, 182, 187, 191, 196, 200, 205, 210, 215, 221, 226, 232, 237, 243, 249, 255, 261, 267, 274, 280, 287, 294, 301, 309, 316, 324, 332, 340, 348, 357, 365, 374, 383, 392, 402, 412, 422, 432, 442, 453, 464, 475, 487, 499, 511, 523, 536, 549, 562, 576, 590, 604, 619, 634, 649, 665, 681, 698, 715, 732, 750, 768, 787, 806, 825, 845, 866, 887, 909, 931, 953, 976);
   res2 = new Array (1, 1.02, 1.05, 1.07, 1.1, 1.13, 1.15, 1.18, 1.21, 1.24, 1.27, 1.3, 1.33, 1.37, 1.4, 1.43, 1.47, 1.5, 1.54, 1.58, 1.62, 1.65, 1.69, 1.74, 1.78, 1.82, 1.87, 1.91, 1.96, 2, 2.05, 2.1, 2.15, 2.21, 2.26, 2.32, 2.37, 2.43, 2.49, 2.55, 2.61, 2.67, 2.74, 2.8, 2.87, 2.94, 3.01, 3.09, 3.16, 3.24, 3.32, 3.4, 3.48, 3.57, 3.65, 3.74, 3.83, 3.92, 4.02, 4.12, 4.22, 4.32, 4.42, 4.53, 4.64, 4.75, 4.87, 4.99, 5.11, 5.23, 5.36, 5.49, 5.62, 5.76, 5.9, 6.04, 6.19, 6.34, 6.49, 6.65, 6.81, 6.98, 7.15, 7.32, 7.5, 7.68, 7.87, 8.06, 8.25, 8.45, 8.66, 8.87, 9.09, 9.31, 9.53, 9.76, 10, 10.2, 10.5, 10.7, 11, 11.3, 11.5, 11.8, 12.1, 12.4, 12.7, 13, 13.3, 13.7, 14, 14.3, 14.7, 15, 15.4, 15.8, 16.2, 16.5, 16.9, 17.4, 17.8, 18.2, 18.7, 19.1, 19.6, 20, 20.5, 21, 21.5, 22.1, 22.6, 23.2, 23.7, 24.3, 24.9, 25.5, 26.1, 26.7, 27.4, 28, 28.7, 29.4, 30.1, 30.9, 31.6, 32.4, 33.2, 34, 34.8, 35.7, 36.5, 37.4, 38.3, 39.2, 40.2, 41.2, 42.2, 43.2, 44.2, 45.3, 46.4, 47.5, 48.7, 49.9, 51.1, 52.3, 53.6, 54.9, 56.2, 57.6, 59, 60.4, 61.9, 63.4, 64.9, 66.5, 68.1, 69.8, 71.5, 73.2, 75, 76.8, 78.7, 80.6, 82.5, 84.5, 86.6, 88.7, 90.9, 93.1, 95.3, 97.6, 100, 102, 105, 107, 110, 113, 115, 118, 121, 124, 127, 130, 133, 137, 140, 143, 147, 150, 154, 158, 162, 165, 169, 174, 178, 182, 187, 191, 196, 200, 205, 210, 215, 221, 226, 232, 237, 243, 249, 255, 261, 267, 274, 280, 287, 294, 301, 309, 316, 324, 332, 340, 348, 357, 365, 374, 383, 392, 402, 412, 422, 432, 442, 453, 464, 475, 487, 499, 511, 523, 536, 549, 562, 576, 590, 604, 619, 634, 649, 665, 681, 698, 715, 732, 750, 768, 787, 806, 825, 845, 866, 887, 909, 931, 953, 976, 1000, 1020, 1050, 1070, 1100, 1130, 1150, 1180, 1210, 1240, 1270, 1300, 1330, 1370, 1400, 1430, 1470, 1500, 1540, 1580, 1620, 1650, 1690, 1740, 1780, 1820, 1870, 1910, 1960, 2000, 2050, 2100, 2150, 2210, 2260, 2320, 2370, 2430, 2490, 2550, 2610, 2670, 2740, 2800, 2870, 2940, 3010, 3090, 3160, 3240, 3320, 3400, 3480, 3570, 3650, 3740, 3830, 3920, 4020, 4120, 4220, 4320, 4420, 4530, 4640, 4750, 4870, 4990, 5110, 5230, 5360, 5490, 5620, 5760, 5900, 6040, 6190, 6340, 6490, 6650, 6810, 6980, 7150, 7320, 7500, 7680, 7870, 8060, 8250, 8450, 8660, 8870, 9090, 9310, 9530, 9760, 10000, 10200, 10500, 10700, 11000, 11300, 11500, 11800, 12100, 12400, 12700, 13000, 13300, 13700, 14000, 14300, 14700, 15000, 15400, 15800, 16200, 16500, 16900, 17400, 17800, 18200, 18700, 19100, 19600, 20000, 20500, 21000, 21500, 22100, 22600, 23200, 23700, 24300, 24900, 25500, 26100, 26700, 27400, 28000, 28700, 29400, 30100, 30900, 31600, 32400, 33200, 34000, 34800, 35700, 36500, 37400, 38300, 39200, 40200, 41200, 42200, 43200, 44200, 45300, 46400, 47500, 48700, 49900, 51100, 52300, 53600, 54900, 56200, 57600, 59000, 60400, 61900, 63400, 64900, 66500, 68100, 69800, 71500, 73200, 75000, 76800, 78700, 80600, 82500, 84500, 86600, 88700, 90900, 93100, 95300, 97600);
   e = 96
   calculate2();
}
function doe24()
{
   res1 = new Array (.001, .0011, .0012, .0013, .0015, .0016, .0018, .002, .0022, .0024, .0027, .003, .0033, .0036, .0039, .0043, .0047, .0051, .0056, .0062, .0068, .0075, .0082, .0091, .01, .011, .012, .013, .015, .016, .018, .02, .022, .024, .027, .03, .033, .036, .039, .043, .047, .051, .056, .062, .068, .075, .082, .091, .1, .11, .12, .13, .15, .16, .18, .2, .22, .24, .27, .3, .33, .36, .39, .43, .47, .51, .56, .62, .68, .75, .82, .91, 1.0, 1.1, 1.2, 1.3, 1.5, 1.6, 1.8, 2.0, 2.2, 2.4, 2.7, 3.0, 3.3, 3.6, 3.9, 4.3, 4.7, 5.1, 5.6, 6.2, 6.8, 7.5, 8.2, 9.1, 10, 11, 12, 13, 15, 16, 18, 20, 22, 24, 27, 30, 33, 36, 39, 43, 47, 51, 56, 62, 68, 75, 82, 91, 100, 110, 120, 130, 150, 160, 180, 200, 220, 240, 270, 300, 330, 360, 390, 430, 470, 510, 560, 620, 680, 750, 820, 910);
   res2 = new Array (1.0, 1.1, 1.2, 1.3, 1.5, 1.6, 1.8, 2.0, 2.2, 2.4, 2.7, 3.0, 3.3, 3.6, 3.9, 4.3, 4.7, 5.1, 5.6, 6.2, 6.8, 7.5, 8.2, 9.1, 10, 11, 12, 13, 15, 16, 18, 20, 22, 24, 27, 30, 33, 36, 39, 43, 47, 51, 56, 62, 68, 75, 82, 91, 100, 110, 120, 130, 150, 160, 180, 200, 220, 240, 270, 300, 330, 360, 390, 430, 470, 510, 560, 620, 680, 750, 820, 910, 1000, 1100, 1200, 1300, 1500, 1600, 1800, 2000, 2200, 2400, 2700, 3000, 3300, 3600, 3900, 4300, 4700, 5100, 5600, 6200, 6800, 7500, 8200, 9100, 10000, 11000, 12000, 13000, 15000, 16000, 18000, 20000, 22000, 24000, 27000, 30000, 33000, 36000, 39000, 43000, 47000, 51000, 56000, 62000, 68000, 75000, 82000, 91000);
   e = 24
   calculate2();
}
function  calculate2()
{
   clear1()
   var r_atten = new Array (100)
   var r_g = new Array (100)
   var min_diff = 1
   var decade = 1
   var seed_decade = 1
   var i, j, k, l, div, diff, seed, real_div, real_div_2, error, input_voltage, output_voltage, test_ratio, r_atten
   ratio = parseFloat(document.theForm.ratio.value)
   seed = parseFloat(document.theForm.seed.value)
   if (ratio < 0.00001 && e == 96) alert ("Ratio too low");
   if (ratio > .995 && e == 96) alert ("Ratio too high");
   for (i = 0 ; i < res2.length ; i ++ )
   {
      for (j = 0 ; j < res1.length ; j ++ )
      {
         test_ratio =  (2 * res1[i]) / (res2[j] + 2 * res1[i])
         diff = Math.abs(ratio - test_ratio)
         if (diff <= min_diff) min_diff = diff
      }
   }
   k = 0
   for (i = 0 ; i < res2.length ; i ++ )
   {
      for (j = 0 ; j < res1.length ; j ++ )
      {
         test_ratio = (2 * res1[i]) / (res2[j] + 2 * res1[i])
         diff = Math.abs(ratio - test_ratio)
         if (diff == min_diff)
         {
            r_atten[k] = res1[i]
            r_g[k] = res2[j]
            k = k + 1
         }
      }
   }
   if (r_atten[0] > 0)
   {
      document.theForm.c0.value = r_atten[0] * seed
      document.theForm.r0.value = r_g[0] * seed
      document.theForm.caption0.value = "Choice 1"
   }
   if (r_atten[1] > 0)
   {
      document.theForm.c1.value = r_atten[1] * seed
      document.theForm.r1.value = r_g[1] * seed
      document.theForm.caption1.value = "Choice 2"
   }
   if (r_atten[2] > 0)
   {
      document.theForm.c2.value = r_atten[2] * seed
      document.theForm.r2.value = r_g[2] * seed
      document.theForm.caption2.value = "Choice 3"
   }
   if (r_atten[3] > 0)
   {
      document.theForm.c3.value = r_atten[3] * seed
      document.theForm.r3.value = r_g[3] * seed
      document.theForm.caption3.value = "Choice 4"
   }
   if (r_atten[4] > 0)
   {
      document.theForm.c4.value = r_atten[4] * seed
      document.theForm.r4.value = r_g[4] * seed
      document.theForm.caption4.value = "Choice 5"
   }
   if (r_atten[5] > 0)
   {
      document.theForm.c5.value = r_atten[5] * seed
      document.theForm.r5.value = r_g[5] * seed
      document.theForm.caption5.value = "Choice 6"
   }
   if (r_atten[6] > 0)
   {
      document.theForm.c6.value = r_atten[6] * seed
      document.theForm.r6.value = r_g[6] * seed
      document.theForm.caption6.value = "Choice 7"
   }
   if (r_atten[7] > 0)
   {
      document.theForm.c7.value = r_atten[7] * seed
      document.theForm.r7.value = r_g[7] * seed
      document.theForm.caption7.value = "Choice 8"
   }
   if (r_atten[8] > 0)
   {
      document.theForm.c8.value = r_atten[8] * seed
      document.theForm.r8.value = r_g[8] * seed
      document.theForm.caption8.value = "Choice 9"
   }
   if (r_atten[9] > 0)
   {
      document.theForm.c9.value = r_atten[9] * seed
      document.theForm.r9.value = r_g[9] * seed
      document.theForm.caption9.value = "Choice 10"
   }
   real_output = 2 * r_atten[0] / (r_g[0] + 2 * r_atten[0])
   document.theForm.real_output.value = real_output
   error = ((real_output - ratio) / ratio) * 100
   document.theForm.error.value = error
   opamp_gain = (2 * r_g[0]) / ((r_atten[0] * r_g[0]) / (r_atten[0] + r_g[0]) + r_g[0])
   document.theForm.opamp_gain.value = opamp_gain   
}
function clear1()
{
   document.theForm.c0.value = ""
   document.theForm.r0.value = ""
   document.theForm.c1.value = ""
   document.theForm.r1.value = ""
   document.theForm.c2.value = ""
   document.theForm.r2.value = ""
   document.theForm.c3.value = ""
   document.theForm.r3.value = ""
   document.theForm.c4.value = ""
   document.theForm.r4.value = ""
   document.theForm.c5.value = ""
   document.theForm.r5.value = ""
   document.theForm.c6.value = ""
   document.theForm.r6.value = ""
   document.theForm.c7.value = ""
   document.theForm.r7.value = ""
   document.theForm.c8.value = ""
   document.theForm.r8.value = ""
   document.theForm.c9.value = ""
   document.theForm.r9.value = ""
   document.theForm.real_output.value = ""
   document.theForm.error.value = ""
   document.theForm.caption0.value = ""
   document.theForm.caption1.value = ""
   document.theForm.caption2.value = ""
   document.theForm.caption3.value = ""
   document.theForm.caption4.value = ""
   document.theForm.caption5.value = ""
   document.theForm.caption6.value = ""
   document.theForm.caption7.value = ""
   document.theForm.caption8.value = ""
   document.theForm.caption9.value = ""
}
</script>
<form name="theForm">

    <table cellspacing="0" cellpadding="1" border="1" bgcolor="#33CCFF">
        <tbody>
            <tr>
                <td>
                    <table cellspacing="0" cellpadding="3" border="0">
                        <tbody>
                            <tr>
                                <td align="right">
                                    <b>

                                        Attenuation Factor (Vout/Vin): 

                                    </b>
                                </td>
                                <td>
                                    <input value="0.5" name="ratio"></input>
                                </td>
                            </tr>
                            <tr>
                                <td align="right">
                                    <b>

                                        Select Resistor % Tolerance: 

                                    </b>
                                </td>
                                <td>
                                    <select name="seq">
                                        <option value="96">

                                            1 %

                                        </option>
                                        <option value="24">

                                            5 %

                                        </option>
                                    </select>
                                </td>
                            </tr>
                            <tr>
                                <td align="right">
                                    <b>

                                        Select Resistor Scale (Ohms): 

                                    </b>
                                </td>
                                <td>
                                    <select name="seed">
                                        <option value="1">

                                            1

                                        </option>
                                        <option value="10">

                                            10

                                        </option>
                                        <option value="100">

                                            100

                                        </option>
                                        <option value="1000" selected="">

                                            1000

                                        </option>
                                        <option value="100000">

                                            100000

                                        </option>
                                        <option value="1000000">

                                            1000000

                                        </option>
                                    </select>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                </td>
                                <td>
                                    <input type="button" onclick="calculate1()" value="Calculate"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <b>

                                        Resistor One R1 (Ohms)

                                    </b>
                                </td>
                                <td>
                                    <b>

                                       Resistor Two R2 (Ohms)

                                    </b>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c0"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r0"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption0"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c1"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r1"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption1"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c2"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r2"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption2"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c3"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r3"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption3"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c4"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r4"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption4"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c5"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r5"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption5"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c6"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r6"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption6"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c7"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r7"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption7"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c8"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r8"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption8"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="c9"></input>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="r9"></input>
                                </td>
                                <td>
                                    <input size="10" style="background: #33CCFF; border=0" name="caption9"></input>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                </td>
                            </tr>
                            <tr>
                                <td align="right">
                                    <b>

                                        Actual Attenuation: 

                                    </b>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="real_output"></input>
                                </td>
                            </tr>
                            <tr>
                                <td align="right">
                                    <b>

                                       % Error: 

                                    </b>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="error"></input>
                                </td>
                            </tr>
                            <tr>
                                <td align="right">
                                    <b>

                                        Stability Check (>1? ): 

                                    </b>
                                </td>
                                <td>
                                    <input style="background: #33CCFF; border=0" name="opamp_gain"></input>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>
        </tbody>
    </table>

</form>
</font>
