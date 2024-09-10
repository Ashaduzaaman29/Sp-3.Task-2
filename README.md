<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Company</title>
    <!-- Favicon -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <!-- External CSS -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Internal CSS for demonstration purposes */
        body {
            background-color: #e0e0e0; /* Background color */
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007BFF; /* Header background color */
            padding: 20px;
            color: white;
            text-align: center;
        }

        .container {
            padding: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse; /* Collapsed table border */
            margin: 20px 0;
        }

        th, td {
            border: 1px solid #ddd; /* Solid table border */
            padding: 8px;
            text-align: center;
        }

        th {
            background-color: #4CAF50;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f2f2f2; /* Vertical zebra stripes */
        }

        .quote {
            border-left: 4px solid #ccc;
            margin: 20px 0;
            padding-left: 10px;
            font-style: italic;
        }

        footer {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .highlight {
            color: #ff5722; /* Text color */
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to Our Software Company</h1>
    </header>

    <div class="container">
        <!-- HTML Quotation Section -->
        <blockquote class="quote">
            <q>Our mission is to deliver the best software solutions with passion and precision.</q>
            <cite> - Software Company CEO</cite>
        </blockquote>

  
        <!-- Address Section -->
        <p>Visit us at our office:</p>
        <address>
            456 Tech Ave, Innovation Hub, Software City, SC 12345
        </address>

   
        <p>Customer Support in Arabic: <bdo dir="rtl">خدمة العملاء</bdo></p>

 
        <table>
            <thead>
                <tr>
                    <th>NAME</th>
                    <th>APRIL</th>
                    <th>2022</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>Project Alpha</td>
                    <td>FIESTA</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>Project Beta</td>
                    <td>FIESTA</td>
                </tr>
                <tr>
                    <td>Michael Johnson</td>
                    <td>Project Gamma</td>
                    <td>FIESTA</td>
                </tr>
            </tbody>
        </table>

     
        <h2>Team Assignments</h2>
        <table>
            <caption>Team Roles and Responsibilities</caption>
            <colgroup>
                <col style="background-color: #e8f5e9;">
                <col style="background-color: #ffebee;">
                <col style="background-color: #e3f2fd;">
            </colgroup>
            <thead>
                <tr>
                    <th>Team Member</th>
                    <th colspan="2">Roles</th> <!-- Colspan Example -->
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td rowspan="2">John Doe</td> <!-- Rowspan Example -->
                    <td>Lead Developer</td>
                    <td>UI/UX Designer</td>
                </tr>
                <tr>
                    <td>Backend Specialist</td>
                    <td>Frontend Specialist</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td colspan="2">Project Manager</td>
                </tr>
            </tbody>
        </table>
<h3>Collapsed Table Border</h3>
        <table class="border-collapsed">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Style Table Border -->
        <h3>Styled Table Border</h3>
        <table class="border-style">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Round Table Border -->
        <h3>Round Table Border</h3>
        <table class="border-round">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Dotted Table Border -->
        <h3>Dotted Table Border</h3>
        <table class="border-dotted">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Dashed Table Border -->
        <h3>Dashed Table Border</h3>
        <table class="border-dashed">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Solid Table Border -->
        <h3>Solid Table Border</h3>
        <table class="border-solid">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Double Table Border -->
        <h3>Double Table Border</h3>
        <table class="border-double">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Groove Table Border -->
        <h3>Groove Table Border</h3>
        <table class="border-groove">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Ridge Table Border -->
        <h3>Ridge Table Border</h3>
        <table class="border-ridge">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Inset Table Border -->
        <h3>Inset Table Border</h3>
        <table class="border-inset">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- None Table Border -->
        <h3>None Table Border</h3>
        <table class="border-none">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>

        <!-- Hidden Table Border -->
        <h3>Hidden Table Border</h3>
        <table class="border-hidden">
            <thead>
                <tr>
                    <th>Header 1</th>
                    <th>Header 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Data 1</td>
                    <td>Data 2</td>
                </tr>
            </tbody>
        </table>
    </div>
        <!-- Unordered List -->
        <h2>Our Services</h2>
        <ul>
            <li>Software Development</li>
            <li>Web Application Development</li>
            <li>Mobile Application Development</li>
        </ul>

        <!-- Ordered List -->
        <h2>Technologies We Use</h2>
        <ol>
            <li>HTML, CSS, JavaScript</li>
            <li>Python, Java, C++</li>
            <li>React, Angular, Vue</li>
        </ol>

        <!-- Hyperlink and Bookmark -->
        <h2>Explore More</h2>
        <p>For contact information, please visit <a href="#footer" class="highlight">Contact Us</a>.</p>

      
        <h2>Our Team</h2>
        <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxITEhUTExMVFhUXFxoYGRcXGB0ZGBgYGBcXFxcXFxgaHSggHRolHRUYIjEhJSkrLi4uGB8zODMsNygtLisBCgoKDg0OGhAQGy0lHR0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAKoBKAMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAAGAgMEBQcBAAj/xABPEAACAQIEAgUGCgcECAYDAAABAgMAEQQSITEFQQYTIlFxMmGBkaGxBxQjQlKSssHR8BVTYnJzgtIkM8LhNEN0g5Ois/FEY6O00+IWVJT/xAAZAQADAQEBAAAAAAAAAAAAAAABAgMABAX/xAAkEQACAgICAgEFAQAAAAAAAAAAAQIREiEDMRNRQSIzQmFxMv/aAAwDAQACEQMRAD8AKRY/nz11VoCwfRvFpr8enHjOrD1XavY5eKxsOoxPWKBrnCHXzHqwaKZrD1rgXFz5hv7bU4B56zbB4jik1yMZlAJUgQx6MpyuPQQRfna+m1SV4XxE+VxCU/uqI/aL0bRrZoXprxuRYa+NZ63Ryc+VjsZ//QfdlpqToktjnxOJfzNNf3WrWjbD6bh8LeXFHfvyAe3eqvGcFwB8vq1/3lvYzWoUh6A4Yk3zSWNsxJFwNAeyw5AVNh6CYQf6r1kn7V61moZ4vwPhio7JiIusCkovWRkswBKqApBJJ0570I5aOcZ0Tw8cUjrEgKozA5EuCFJBBy3B0oOKUrNRGIqy4QujeIqGUqz4MmjeIoGRIVKc6gNowBHnF/fToSnY0rDFdJwKBt4wP3br9m1NDodEzACSRQSBya1za4Frn10SwQ3qfg8P8on7y+8U6EaAXinQCZBeGTrtdihiNv5iQfWKj4DoPiS3yqlVtplZSb6b7gC162eSCmWw4rUakZpH8Hx2OY7HWWId/wCPsFWeC6KSw6RzSIO5cSQPUjUanDjurhgHdS4sbQIvwB/nYl/TiMSfdTf/AONwv5Ukba/OEj7Gx8taLpsMLGqbAcPVgSWkFy3ktYeUfMaGLDaK1Oi+GHJfEQKfewqQvAIQNGYeEKj/AB1ajg0XfKf94P6K6vBIOaufFx9yihiNZW/oyEfrT/Mq/wCE134lh+Yf0yr/APHVn+iIP1Q9LN9xFLXhcA/1S/Wf+utiayneHD8lX0yk+61U2L4Rhze6IxuO4al1zEkans5t6Mv0fCNoU9bfe1R8YqqOzHGNVHkA7uoO9+RNaqA9gvFwXBj/AFaeomrDCcLge4VEIH7Pf4+BojggUj+7j/4af004uHUbKo/dUL67AU1M2ikj4JENoox/Iv4VIThS8lUeCj8KtxHTix0KMVacO8/sp1eG/tGrMJS1StQSs/Ra95qo4xhAkkIF95N/BaLMtUHSMfKQ/wA/uFCjMVgsEpUHXWvVLwPkCu1jCBhhSXwqnfN/Kbe2xp2CLLI4Ga2RDYsTqWlBtcm2w27hTznzGr0QspOBtE4ktDlyzSpbNuUcqWNgNTa58asxho/1a+t/6qq+iyaT/wC0zH1yFvvq+C0lDWNCBBtGnqv9omuSKADZI/8Ahp/TUnJSJU0PhRoNjMUYu+gHbbYADRiNhpT4jpcKat+832jToWsYr+MRf2eb+FJ9g1lxirW+Kp/Z5v4T/YNZg0dJINEBoqtOCxDK/iPdUZkqThE7L0thSJDSgDenIp0+mvpIoVx8eq+n7q7DHRA2aFhIjp59qv8Ah2BJZdOY99B36RnR2VZCFRcPZcqEWaDOw1W+pHfRrnKDEMDYxKrLbTU5jr9WmRmXL4B/oN6qbPDZPomnWxEixCTrGJzKtidLNKI/cb0QmmsUF/0XJ9E+z8a83CZfoe0fjRPXaGQQSk4VNY9g7fSX+qqHh0dhbzt9o1oM40bwPuNA2FX7/eaIELIpQFKtSgtYYby121LtXbUAjLCoOPTT+aP/AKi1ZsKi4xOz/NH/ANRaBh7DR6U7kpzDppTuWiYZCUsJToWlBaARoLSwtLy10CgYby1QdI17cX8/uFEmWqPpGnaiP733VjM9gfIFepWCXsCvUDE9kRZWzMq3SO1yBftS7X8akqsHORfrLUXCJiuvF3Yx/GJtMth1PVKIxe3KS9ubXuLiiRVqlkqM2wGJCSYgIhZfjEliCO8VYLxM/qm9Yp3CwDrMT/tMn+GpHUVgpEX9Jt+qP1hXjxBjp1R9dTRCK8YRQ2NQ/h4ZyMyxAhixHbtzO4tpS+oxH6kfXH4VecJ/uh/N9tqWCb1kBg1xCHEdVKDEAOra5zg2BU62rOnirYuIn5LEfuOP/T/zrKpo6WQ0dlW8dSMGnZeuyJTuEXsv+eVIOkDnEo9V9P3UlAFUsTYAXPgNakcU8pPBv8NRMYgeMx3sWtr3C4J91MicuxrE9IY5MRnAZVKxJdtPIRIyTY6A2O/I62rUOKT4kSYhYo42iKx9YzEhlWzXKi4B7Nzz2rPOB4YQylnFhZfJtlYE5RuD2ST69N61fF2tjP4Y+zJTJhcaHsbLirABI/i/WRdq/b/vUJ0zfT022opcYjkUqmxpAwwH/mR/+5SiamYhX2xPfHSXXF8jH+fRVlXSaWwg/KMZrcpaxvoNtb8qDGxEyk5ctrncec1ok81w37p++gqGO/rPvNMzRKx8dif2PVSf0hiu5PVVycPSfiwpHY9Ip/0jiu5PVXf0hiv2PVVr8VrvxelthpFV8fxP7Hqp7CtPKchKglkANtAc2l/NpU/4vUjAQ2dP4sf2jQthpDo4VjV0zxn+Wvfo3HfrIh/LRXKN65Cmb2++rUiOTBU8Mx/62L1f/Wm/iGO0/tEGpsNNz9SjP4uO81GPDl7Ordk3G3eDrp5q1I1yBn9FY/niYB6P/pXm4Tjxf+0w3AuRbW3h1dFL4NWsSSLV2eMdtr6lTp4ClpBtgliOD8RUX+MxerzX/V1QdJYMSgjV5Azgk5lGliAQNh391aVxA9g37iPWpoQ6Xx9tPD/AlZr6bMm8qBCLHYkCwf2D8K9V7hMApUEj83r1TtlKDy1PKKH4+LTXs8Lx6Egt1dja1wMkjG+vMU5+lpL8rej8Ko5Jdk4py6KzCj5TEf7RJ/hqRam5uIRoX+SuT8oxDblt7efT3VdSRR5b2A08bUVJPo2LXZWWrjrpVX0pxFsNMsUuWUxHIRowJ0BHMag68qzPoBxHExY/4u0hdXDdYGLMNELBwTqDewvzvbmKFq6G3Vm/8L/ux4v/ANRqcA1Bv+biofDMZHkYBgcrPfzXdj67HanEx0Vl7aX560RT2KF4Zv3X+xb7qzbFQ2rRZcQnUyAOtyH0zDnmtz7qB8VHpSyGgUEq0rDjsvS8QtNxHsv+e+pooUXEEvIn7rf4agubOoHf+JvU7F+WlvoN6rpeoTuOsQcrm/oBq0eiMuwg4zhbYSNu6VPHtW/pF/C9G3EXs2N/hJ7pax/H9KpZgI1CrGrAre+YkAgFjfax2HtrScJxBp4p5yuXrMNExAvYN8uGAPmP3VkzMK+KvaMC4/vYf/cR0YUHcWHYOg/vYNbm/wDpEWw9NF9qLMLFIxBsKo+lHSIYNVbIXZyQovlGgBJZuQ1FK4Jxw4lGzJ1bKBezBh2r21GoOmx7xvS/JqdWPSPvy0NC2E+9vtGikkWPgfvoYwQ+/wB5qkgRJJWvZa7S1UnYE37udION5K9kp4xkAEggHavZaASOVpeGHaT+JH9o0tlpWHXtL/Ei+0aVhCJ3BOXv/P3VxoWIsLaE1w26wa/mxpnrGztl3/P+VWo5x/4q1+XrP4VEPDXunaHZa58+oNqWs83c31f8qQevJTfyu1sNMw+69FWvk2ieuHutiefusa9LhxeR7+Ulrd1gedI+LlltexuPPtYmlSwayNfQqRbu0/yqY41xVfkyPH3GhXpQO3H/ADfZjor4oLoR+djQr0m1kj8G9yUfxMv9DWAXsD8869TuCXsD8869UypziLWEbgmzKTmLEgiym4F7D0VGjxlyBYfWG1tzpQJ0d4xMj/FJ436xdAh1ZRYWC2NmQ2G3tq36TFgQkUgSQKy3CkgMRaxAUnex2+aKnN26Dx0lZL43iHGKVUkFiiEoQChJzCxYC6m4Gu3a25Va4HFSNLEAkir8837OhJvbZlO2a3MbUMcG4XiwpaSOaaxYCTq8pdSVIvGwvezPawI21OorvFMbOs0eaOWJEhlf5RShZljlNhcm6gFefdflVoR2S5JtKy94/LMbrHh2mDxlQoYKGILMLkyrsBfyGOptzrFZ+LYgSiTWJgMoCgqFU6FcrX08b7eYVoXwpdIWXB4fBhsxkBkd9L5AexYDbNdtuQI2NZdh3K7eo7Ec1I7jWlVipuqDDoHxLq4sWhOhjBX99iIyfHtLRbN0twatkMoLXsbJIApvY3JQAWPPas6jeFYmETSZnVGcOFCjI18qOGJbW+4B7NV3EMRncvsWCk/vZFzetrn00XtGjJpm1YHGpJYowZSd1Nxv5qmYkVmnQHHlHWNjYFhYHTVmrSZ2qRZO9lJjRURT2X8Kl481BytkchHbT5qMx9Sgk+iguxga41juqMZte4Ye1T91VkvGo21ykEH0W5i/hV5xHoxipQo6piBexLBDqNPKGmuhuDTXR3oo6Yr5ZezHrY28uylNrgizXBB3Xla1OpUibTcgbwHC5ZHCrG/lAElSAt9sxtpX0HwTCCCGOK98ihb7AnbQePKoXCAq2A0vf0nX17VC6W4RsRLFh42KAqZCymxFiFOu4FtNN81T4+fb1/Cj4etknHSFZXt9NvRsfvqV0exj9ciBiFuBlubWuBa21DA4VJKc4xmJBYBrAoV1A2DISPWaewvCsXGwdMdJddQGiia5GtvJplCV2B8saoP+J8WiAW8YkbMRlcaqNbnyWGuUeikPxOKIfJwqC1rgBVBttcgbDwoe4zLaWQftsP8AmNN43EXIArZsXEO0ZCoJUC4Bt4i9DXHcZBFLHEmFnlco0oEMojAVGRSWzSoCMzrprvVlLPZVH7I91DzSh+JRXFx8UmFjqP7/AApqog/jOmXxdeslwLwx3t1jSYfLrsB1cjMx02UE1WYP4TYsW/Uw4eQvqVBlSJiBqcjEjkL2BvYHTShj4asMR8WcaJd1ygADPZSGNudgw17vGsygnZHV0Yq6EMpG4ZTcH0EUPkx9BzcelHViXCsqGSNM/wAYjYr1siRBsqr2tXWrzD4RALZmbXdiCfdp4Cs4XplhMThluY4cT12GZ1ICg5cTC7sj7FeyWsTcAa7Xo84fiQwurBhyINwfAiiqZtkqeNQyDkxtcsAeWwtrvVE/GWVtEXsup1J1yk6em5olUA2uAbbebwoHxHlnxNS5W10VhvsJo+k4N2Mevdm7/RUaLpSVnJMHyZTV+s7WfNtly7WF739FUArhNTXLP2F8cQ+wXGxKuZENgbdo21sDy8arZOm+BBscZhRY2YGUXGuu5Gu9MdGjaL+c+5a+fcfGpeTQXLP68xroT0mQfZ9ODiUJX+/jFyD5Vu6vNi4i0h6+Mqy2UdYNDax0vYVjHRHiBlwqdps0fyZ7RHk2y8/olfbVsZG+k/1m/GpvlaLLiTVmqY/ExuhCyIfB17j56HekLL1qHMtrHcjuTnQQ87fSb1399RpJn+mfZ+FDyuqo3i3dmh4SRMo7afWH416s3M7/AEvYv9NeoeQbArJvg0xSm8eIjPd5afZBtXcP0a4zCQYpzptlnNvU4A9daAtl3ndvMAB771yTiAG1z4n8KORPEmdHuNGHCQri87z5T1lhnN8x3I0Oltj6qTxDpXgVYSscUMq6gYaTJbW+YlLc9weVVL4q52FIlxBynXlR8pvGBfTlo8e6TYRZ5D2gSYGVMhJZbNqDYlhy3FV3B+iM+cNLC1hqBmQC/wC1ds3srQuERokSqosBmsO4FibeGtTTIO4Usp2GMa2COL6KrKLMkcR3umtzlYZSABpcg3vrrtTvDOg8Iy9awksALZLA2FhuTRTZDyFdVFoKVKhnG3Y1hujGEGQ9WewwZRmICsDe4APeKvPi6AElR6dffUKKW3dT/wAaJFrCjaBjXQ9w943UOmUqwBBAGoNSJn7J8KGejHDZcLdDKJIjqFylSrd4NyLHmPT437Ekab0bBTIhNDvEJyuJfuOT7OvuNFJil8xoU4vwvEGZmETkFgbqCdBGq8vODSTeh4LYQ8P+YeYS3pOp+710iV2bEF1ZcqQ5ASwA6zMxOm9tQPRTM0M/VuIwEc6KXNrC5uQLHUC1r1VYbo04teYc7gG3tsahxtxeRaSUlRFgx2KiyiRMPbY5JWJ0GlgU19dTuI8VKwsVVs52IZQBdgALlvLudu/Sp8DwwLaAYMyEFSHdg5B3DMwJIJA02qqbgWaNoerjhVyDeKZWWPKcwyIxVspJa4zDuBHK0eSd22TlxwSqKJ+Jm8lmNmKqzX+kwu3tNO4LjECESEhUXS/n8/roY6ccWaGNVWxJIW50tYbkDcabXrPvjOeVWlkLAkBtLALfYBgBbzWAp4q9olJ1o3VelEWILiKxVGCtIzBVuRewG5I7tNrG1V+I4gYcZFN1M8ydTLGeoiaQqzPA65gNtFNBnRGeOPFs0faRo8pPWoWFiDaONWPd59zYAVoOEfDs1kJY726xRc8yVzg+bai50wqFoFvhK6SJLhxAYJUJdWtKuQ2S+oFy1+VtNCfCssNXvTLipxGJlawVVbq1HcsfZABtoCQWt+0aomOvhT3ZJ6EijL4OOkvxSbq3PyMxsf2JNlfwOin0HlV1w7geFMEBfCxs7RKWbPICTcqSbOBc5b6d9Sf0Fg//ANOP0tIfe9T8qTKLjZpEPFE+dce3191BHSuD5eTDlrKsBxBbVDZXAPb1HO1tzY+anBN/5YOltWY6Wy7ljyNRuIRNiUljEKGTIlm3exZtmOotkJ31v69DluSsPJD6XQX8LwPyCjMoLhXynl2RdR32vvUDi0seHI61lAPj+FUPFMTjMImHlWIu6RKmuZgGZWUlgvdmvcb2FzpQpiMc8rkTjEyObkkTBQbfRiDhFAGwA9dUVMV2qNVw/HcOSgjZbOdMo0J/HSsf4ZiOGqf7RFipZG3s0axgk37IDq3eLs3oHK7fgqQpG8LzvinfsRI4yroTmkeSEDKANSNswF/nEBx4yu69m6sV7Hk9kkdk3JK6aG+oqj2iXTCvC4mDCYiYDrEhkc2U9WxiYdoKSkrXXK47X7NtSDVxx/Hrh5DGsiOVtmykZhoLlRfUqT5JsSBfvoFjx7M4LlbFkuWHIOrXY8+fovVpH0exUmgKN1agZDIF20BF7AhgM1wbnvuKjOCY2cqpBOsrMey6gA2kDKQwzKWFtAdLWNwN+ViK85HKo2CwSZGk+LtERZQzOc+h1ABJzDJa+umUnutIlmvbbQctz5z3moNUyvDdbEGvU1JMBuQPE16sVZemaoM/FEVihLZha4CM1r7Xyqd6RiMakfluq/vMB76pIcXFLOxElw00Q08kxqnabfUqxIGh5+arcMM5UyHLPCNoJIpGa1o5jfY9TJr4dinpIpCCOqm2/VSf00U9HMF8gjZ2ym9ly6ABiBoDoCAKuPi697Xtvrp91VfBFPsRcraALDQSqoBilGmvyb/hSwXvbq5PqN+FHcKm3byk33C2003uTc793hTixr9AeofhQ8MQ+SQAyh18pJB/KaabiAUXKyWys1+rbyV0ZtthzNaNZT80equZF+gvd6L68vZW8Mf2bySM5bjMYOUiW+aNLdU/lSi8S7bsNR31yLj8ReNPlAZC6pmRlBMdxILkbqRY1pDRrtlH50FYgigY7DgK4Amxe6gRntTW6ogC4AFjqdRQfEkrMuR2kzQIZasIXqmgerOFqhZeiej1IRqhRmn0NMmBomo9OaHcA+NRVNPK1OLR6TAQt5UUbeKKfeKYj4FhQbrh4lJ5ogQ+tbVLDV0NR0ArcT0YwbrlaBCP2rtryJzE661S4/4O8EVJihQONQDopI1AuliPHWi3PSkfWtijWzMsOQv+p5WsJG2vf5xuNu+prdKIcHHm+LCNSQMwYsb62voW76hhtT4n31R9Of8ARf8AeJ99c0dujok6jYPcZk4c5aRGnzMxbIlgi3JNh1kd/b+FUeMymwjQqLaX1Y32uaajW5F+8e+iPAIcS5hkmssGsebKBdXJZSzEHXYWNtu4X6ejkvIOsLiWAjQxuCFUX7OQLa4OjFtc17ZasCp+lH63/wDipjhxEkSSWAzKOZ0FgB7AKkiI+auRtWdKToUFW2sgzdwDW9eT7qpuM8Rlwsc00LDMOqHaFxZmYA8jzf1VeLA3cNap+kOHUN1c1hC6AyMcwC5H7LEp2hZnHmOgO9NB76FldA+nwk435wjNv2be+9Pp8KGI+dCjfzfdloMxkarI6owZAzBWGuZQTlOw3FuQ8BUdq6KRDKRtmC4hBicKkk0OUYhGQrHbYhlOt1Oo9/pqBiehvC316iddPm9Z6NLkVV9GeNyRwRRrFG4SJNXBPlqHNu7ceqr2HpLrZsJGT+yLUVNdDY2DfSPonhYYUlw0WILCVAQzAAKGDMWDm58iw1GrVQxYqeDEKq5WckFYo3Eps+8RKE6m1wNwSDsddDxvEsHMoE/DwwF7XAa17Xt2dL5Rt3CqvDcM4KJL9XPGzElVV2Sw0BVMrKcuuu+9G0K4st8Vg45MPI0glR0QyIlsuyknrAy7Ai2h76Cw9/P4KPwrQ8eCYcRv/o7KouWIAUhVuSST5zqTc86zgwSc0f0gge6pyKxI44TBckodTc9thr6DXqdzEb2FepbfsakQIOi8VyWZmN76Cw350V9F+GZUUo5jUTMwFicpTsdYeROhrhh7yfRp7qtOjnEo44lBN8zy6CxItK5udbgdr88+/jW9HA99hpwiHJDEvcgqbJqCDY3BFu/SmoH7KnvUH2Xp0NSsoc1HPmNLDvtShm+ivt/CvX9499O3oGEAt3D10o5vNXb169YwnXTaslxuHQYjDESliHmOW4IXMsxbJbYdpSb8ya1u9YrwgoWQokd+sZmdfKJaNzZtLndrcuz36UX9uX8B+cQpgNWuHNVEFWsBsLnlXn2dpOjp9KqV43hha88Qv+2PyKsMNjEdrIyt2c11IIOtjqPR66ZGJq04ppsCnFp0Kx0Gks1dqDisUBpTisldZSleqM8VF9NalwY9TWTFM7wM2KacRNhmGbrCDla5EZysR9IBrAkd9ROnAIw5UggiRQQdwRcEGivoEQZp5mn68okcKNly2FySiL+rBCANYX7Wmhqt+EXDBXIzZ7srm9rg2bsm3dYWHcRU8KaY+dxaZnXxcosL2F7nz6qWIuNOY281PYThPXlysil1JlZWGW6BszMp1vba177d9NcS4g+VYrCym4N9dQb3Fu9jzqqJ/J19NWkr6OeLrs1YdIMPh4lUybDRRlL/AFVGnjoKZ4Zx9mZ5ZZURGAEcOZbqu+Zz9M9w2FZgSbW/7U0IyADbS5HpFiR/zD11LxIr5WbKelMA3nj83bX8apOk3GIMQjAShiImy5XuM7MgUMBuPKNvNflQHhcCWKkgMtwSNri+ouNrjnV7w3hTE2y00eCnYsua9FfDwiVvJAPpt77VzGcHmiUvIhVRu11troNjWkcJ4cFGooLxuO63Hyo8j/F41clVYqto4ydlY65ue+mw2qrhQll70fQqgBFiI4gQe8RqCKtGjB3qv6MSFowzG5McZJPM5F1q1z2+beuZrZ0roaWG3M0/h0u6/vD2EE+6pEFm3Ui/s9lS4YACCO8e8UaNZL407LBiiu4gktfvAa1ZYnHMQu6xn0EffWu4yDNFOPpI6+sGgWXo/wCb2VRxsnbRSL0om5x38HI+416pkvACOVepMUHJkfHdJYk7z6PxsD6DRRwHhpbDwSZH1jD7ZtZBn5g6DMLAW251kwigB1Mkp/ZAjT6zZmI/lWtGwXTKeGOONYIrLGiEkNclVC9+ouDXVDlpnO+O0anGhCqOzooG/cLU4txuRWYD4Q5AzZoo8tzlsDmtdrZrvvbJtp5XmqPiPhDnC5ssAB2ZkbLfsc+s11z+te432UfYd+jVQwHMUrrx+SPxrGm+ETEc2wf/AA2+96Qem0ra3wfogJ/xVso+zb9G0HEDvHrX8a4cSvePrL/VWPYnjmKRBI6wohAIY4ZgpDeTY3sb1APSxtfl4Rfe0GtFSh7A8/RtrcQhG8iC37S/cayeLhi4RYlz5izs7EixvkC2tc9/earZOlwO04UeaP78vfr6Kl4jBYzEiOWOzKAWTNYBg3nvfw0Hn84nPjUGvYYRm5J10X+ExIq8wTX2oKwcGKQ/K4d1A1JTt3HO2W+tFHD+OYEjq2coSLFZAVOo12rgZ2JldxngSFs8JVsxIMakEhl1bKByHMcr92w8VjvyuOfnq0j4qYsTiGiIdEGQOdmzkSEKRYCxFiF0uu1CUuDV2LA5b8rnTzXFNHYJOugpw3Ep08iaQfzlh6muKtcD0nxKeWRIP2hlPrS3tBoCXCzL5MjesH7VPpicUvIN4qR7RVaJ5fo0HiPT6OBVeWCXKTYmMqwDcgc2U6jbXke7WRwPiWF4jm6n4wCPKJQqoO+UubrfXYG9AEHF5D2JMMsimwKXuG1FgVI7wPPe1q1vo9IscCr1C4dR5MIIzAHU5lGxvfmb7mxuAaBdlfJ0RYeRPbzMt/aGHuqjjndJGRiCVYqSNtDbS/KjZ5ix127qAcQ/9qn/AIr/AGjWaNYL/B/xNo8fGqgHrA0YvoLlcyse+zJ/zHvol+EbAsFPU4bEMQ12YK753Nzm52Ua+7uuDwYMwYvChjr1kIYL81g6iSPPszi/aI0DEr82t9wzqRYAiwAseX4n00WrBB6Z8x4jMrHrVYMeTdk+oim7jcV9M8QjS3bPoOt/RWP/AAicWwbBoIIIxKGs8qxqpXKe0ua12PI8vOa1iuNAYEIVWIsGFweR7/UdKkYrDj4sJBe/XEcrWMa+2476TgcRZVzKGW+xVTbc6ZlIGvm1qxg4myx+RGVzklCi2IIsCbAC+4251rAkhHRzKykXsQeXMHzc+dHGBYAbUEYLGrnuIYlWxuVRlYeprEeFEOCx4LiIHXIGHPTMQSTz3Ht7hVoT0TlHYStixb/Osx4lwyZJnYMRmZmzAkHtHN471oiQv9EHwoc6QM2t1sPOLU0qYu0WnRgWiUd0cf8A01q9itfW1D3RyYZQLjyI+f7C1cCInv8ARXG+zsj0XES87aD8/hUhBt4j3iq7CR2tqTU9OXiPeKZGZfKRex5mw/PgKW2EU8hVOuM+VY9xy+o627tRY9+UVbpixani7JsZl4ah5V2lnFrXqxj5vXDMRe1l+k1lX0M1gfRVnw7oxLLqsbsO8DIn15APYrVqWC4RhYTdIhm+m13f67Xb213imOjijeVybKL779wHnJsB41zPmfwi64Eu2B+D6KQRH+0YmCI6HIjKX83bl28VQVdxJwmMXEsBfT5R5lkkHgzsbd2nfWXY6aSZ2lfyna59PIeYAAegVGKnvH1h+NO+NvtiLkS6RpPEumuFACrh42AFo3zIxFrgEprl/dJ11oS4rj48VKZJHWKyBQI4gQ1i29nAG++ulu7WjI84+sv417q/OPWPupowS6FlyNhK/SHrIssjycyyKUytfU5gV2vfS/oNTBi+GBQGRWZjZiIyoRRc9khdzoLjW2umlCXxdggexyE5Q2VspO5UNltfSurETsh9Ac/dRxRs2HL4rhRUApHYW0CZNtRmY9tvZe+tEfBuPRNH8kiLGpygAheQNlWwHMc6yZcBMdopT4Rufuo/6M2w+DDTwv25CBGyDNISNF1YMBZCddLXvU5wVFITbfQVScZXQRyQ5r6q7WPhYag+ikycSdgA2HR15nMWX1GP3i1VPCekWCxDjDSQAsWsLASJzy5jbskDTntvRDLwuKNDkVlA+bFmB7hbIR+RUnUSitmX8BScPMsgkCZSVVr5Qc/zeXPlUccRjTyrjXuv7teVG2IwEYLsrSgvykLsupBvY5rGs/xfC+0ys6ghjYkNZgNLjTx5VaDTJTi4pFlHxCJvJlS/n/A2qywr+f1bUJz8EmUBil1IuGGxHmvaogjZDpmU+a491USJuTXaNCzG66m99Dzv5qNuBbCsr6GYqV8RkaRmXq2NmN9QVtqdeZrVOCaWFEKdl6BWTpiG+PYsbjr5T6nb8K1cP66oMXwVozJMGjby3KtHY82IzhveKYSQBcC4LjMbLFPJ8lEuXJ2cqqgNwkEZ5ec6G97sb1rEUuS4W5Y7km59v/aqThPSeLEz9TCDYRl2k2FwVGVAdSO0e0e7S+9XuUDaiZIiSISbsbmsL45h82KxROg+MTb/AMR63x8I7C6gek29VBHGfgxErvIuIkVndnOZA63ZixAsVIFz3mloLMwweFLkxg67i+mmUk+41Li4RIDqBbxosT4MsXGbpJDJZlIvmRrAnMpBUi2x8rke+rDEdHsUu8Dn92z/AGCaSbaDCKfYKYPDCP5vptf211MbE2ISNrEqc6HkCR2lA/kB5c+e9xNEymzKVPcwIPqNeWAE3sL99qRTHwLaHEU4bnuNQEvUqKWjmzYIQ3A43PaiU+KqfuqVD0Xj5Z0/cd4/sMKl4aarTDz0Mg0QYuAP83ETr/Mr+g9YjVMHCMSLZZ0IBHlwgnQ96Mov6Ks8POKmowp0KRYeHL+fzvU34mLU5HUgGmQGVGIwPdXasmFcogAwk0xisKkilHUMp3B2Njf3ipVeFcB2lOvRvCD/AMPF9QH306OBYaxXqIrGxIyLYkbEi3nNWtq8RRtgpeioHAMKP/Dw/wDCT8KeXhkI2ijHgij7qsLV61HZqRGjw6jZQPAAU6q06BXQKyRrEKKqOk/Rz45GqdYVytmBtm5Ea6jvq9tS46ZKtivemDHRfoIuHcSFmkblyUHXXLzOp3POp3FOlyRHKsUklt2Ayp6GbyvRp56ucc5EbEEg2Oo8KH4o1+KiSwzlbl7donvLbk08YKbtiXiqQO8a6RJPqcRNAL6Lk0v+9E5b11X4bATzZmgmWfbNlJDdwzZgjcuZoiTCxyxEyIrkbF1DEeujDothkRAERVGRdFAA1vfQd9WjClom3b2Z/gBi8No+FYgm57ToNfFWHtq94bLHNcPw95Ce6OBreLMVNvGtESnVUd1FID6AuHoIqSCeAZHNwyOwCqpBuFEaEXvbmatsLwxkOroRzIN7Hu8an8fciI2JG2xtzFQZtI1A0GS+neb3PjR+QUSJMYqnKmre3/IVlPHuk088zxs2WNJGUIuxyMVu53Y6c9ByFaNwsdgHmdz3+NY1N/fzfxZPttQsSQW/Bab4pgNfkT9uOtbhwwHlanu5ek1gfRSZklcoxU9XupIPlLzFbzwZy0MZJJJjUknUk5RqadARNtTbTAbD8/dSb609aiE8sqncW8dv8qbZfNbw2rrb+m1P4YaUDWMZLix1HcdqiS8Dwz+VBH4hcp9a2NWjDWlKK1INgxj+imEVS5zxgfRa/o7QNB4h1Ntr6X7uVHHSw9qEcr7cvKA2oSgGtQ5NPRSPRyCCp8MZpeGFTYxSDDcSsKlxsacjFOoKZC2dilNSBPTaiuNTpiinxVeqLLXq2TMf/9k=">

        <!-- Example of Background Color and RGB Color -->
        <div style="background-color: rgb(230, 230, 250); padding: 10px; margin-top: 20px;">
            <p>This section is styled using RGB color values with padding for enhanced readability.</p>
        </div>
    </div>

    <!-- Footer with Bookmark Link -->
    <footer id="footer">
        <p>&copy; 2024 Software Company | All rights reserved.</p>
        <p>Contact us: <a href="mailto:info@softwarecompany.com">info@softwarecompany.com</a></p>
    </footer>

</body>

</html>
