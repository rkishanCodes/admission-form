# admission-form
<!-- <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CAIAS UG ADMISSIONS</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        margin: 0;
        padding: 0;
        text-align: center;
      }
      .header-container {
        width: 100%;
        height: 20vh;
        background: url("https://i.postimg.cc/76Z4H3y0/Header.png") no-repeat
          center center/cover;
      }
      .grid-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        padding: 20px;
      }
      .grid-item {
        position: relative;
        width: 45%;
        margin: 10px;
        border-radius: 12px;
        overflow: hidden;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.25);
        cursor: pointer;
        aspect-ratio: 1.2;
      }
      .grid-item img {
        width: 100%;
        height: 100%;
        object-fit: cover;
      }
      .text-overlay {
        position: absolute;
        bottom: 0;
        width: 100%;
        background: rgba(0, 0, 0, 0.6);
        color: white;
        padding: 12px;
        font-size: 18px;
        font-weight: bold;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <div class="header-container"></div>
    <div class="grid-container" id="departments"></div>
    <script>
      const departments = [
        {
          name: "Department of Science",
          image: "https://i.postimg.cc/nrMnkvRp/Science.jpg",
          form: "https://docs.google.com/forms/d/e/1FAIpQLSfQqgkJg31N4eqhRXu3NzKNWIQUVQUK72Fnyi4VEvv0gAmFOw/viewform",
        },
        {
          name: "Department of Management Studies",
          image: "https://i.postimg.cc/BZwSvVb6/Management.jpg",
          form: "https://docs.google.com/forms/d/e/1FAIpQLSf2r_UsvF9yvPsCDXUP-t_HJtNKV-1duztN6uiErs_brm7bWg/viewform",
        },
        {
          name: "Department of Computer Science and Applications",
          image: "https://i.postimg.cc/nz3HBd13/Computer.jpg",
          form: "https://docs.google.com/forms/d/e/1FAIpQLScCEWe_IhzzFOa2WryIehumR0qMPRpVzean3rpxzup6bRHYDA/viewform",
        },
        {
          name: "Department of Commerce",
          image: "https://i.postimg.cc/6qSt1ygR/Commerce.jpg",
          form: "https://docs.google.com/forms/d/e/1FAIpQLSdRtpfjTWHObNqIkmfT_iS58VUBJV5ByHPKgxNQibebHmdtbA/viewform",
        },
        {
          name: "Department of Arts and Humanities",
          image: "https://i.postimg.cc/NMssyhRy/Artsand-Humanities.jpg",
          form: "https://docs.google.com/forms/d/e/1FAIpQLSfigKBsh_ME3jVyeNOW0BOyJyfOZsTSd1n_OGeuvueufyp2hg/viewform",
        },
      ];

      const container = document.getElementById("departments");
      container.innerHTML = departments
        .map(
          (dept) => `
            <div class="grid-item" onclick="window.open('${dept.form}', '_blank')">
                <img src="${dept.image}" alt="${dept.name}">
                <div class="text-overlay">${dept.name}</div>
            </div>
        `
        )
        .join("");
    </script>
  </body>
</html> -->
