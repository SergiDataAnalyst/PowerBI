

<html>
  <head>
    <meta charset="UTF-8">
    <title>Power BI Portfolio</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        font-family: 'Roboto', sans-serif;
      }
      header {
        background-color: #1c1c1c;
        color: white;
        padding: 2rem;
      }
      h1 {
        margin: 0;
      }
      nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
      }
      ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
      }
      li {
        margin: 0 1rem;
      }
      a {
        color: white;
        text-decoration: none;
      }
      main {
        padding: 2rem;
      }
      .project {
        margin-bottom: 2rem;
      }
      .project h2 {
        margin: 0 0 1rem 0;
      }
      .project iframe {
        width: 100%;
        height: 60vh;
        border: none;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <h1>Power BI Projects</h1>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Projects</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <div class="project">
        <p>This page features a selection of Power BI dashboards that I have created. Each dashboard is a reflection of my skills in data visualization and my commitment to providing high-quality and easy-to-use data solutions.</p>
        <h2>Project 1</h2>
        <p>This Netflix TV shows and movies Power BI dashboard is an interactive tool that facilitates exploring and analyzing key data about the streaming service's content. With a year slicer, users can easily filter and navigate through the data. The dashboard displays the amount of titles added per year, the total number of titles available on the platform, and the top 5 countries with the most titles.</p>
        <iframe src="https://app.powerbi.com/view?r=eyJrIjoiMmUwZDY2MTAtNDdhYS00YTAzLWE0MGMtODljNDdlN2MxYjcwIiwidCI6ImNmY2M3N2NlLWQxYzctNDI5OS05YWRmLTRkZWJmNmM5NTJhNCIsImMiOjl9" ></iframe>
      </div>
      <div class="project">
        <h2>Project 2</h2>
        <p>This Power BI dashboard showcases data on orders across the US with a state-level view. The dashboard has an interactive date slicer and a category tree that enables users to filter products. The customer order table provides insights into the order types (first class, same day, standard class). The map visual enables the user to explore the order distribution across different states in the US, while the customer order table provides an overview of the order types and their frequency.</p>
         <iframe title="logistics dashboard2" width="1024" height="612" src="https://app.powerbi.com/view?r=eyJrIjoiZGVkYTg0YTQtNmFiZC00ZWJhLTg3NDMtZjhlNjQ5ZDAxNDZhIiwidCI6ImNmY2M3N2NlLWQxYzctNDI5OS05YWRmLTRkZWJmNmM5NTJhNCIsImMiOjl9" frameborder="0" allowFullScreen="true"></iframe>
        <p>The dashboard reveals that the majority of orders are from the eastern part of the US, with higher orders in New York and California. The customer order table suggests that most orders are of standard class and that there is a substantial number of same day orders. The category tree reveals the product categories with higher sales, which could be used to focus on marketing efforts for these categories. First class orders are consistently more profitable than standard class orders, the company could consider offering incentives to customers to choose the first class option, such as free shipping or a discount on their next order. Additionally, the company could analyze customer feedback and reviews to identify areas for improvement in their current order options, such as delivery times or shipping costs, and make adjustments accordingly. </p>
      </div>
      <div class="project">
        <h2>Project 3</h2>
        <p>Description of project 1 goes here... </p>
        <iframe src="https://app.powerbi.com/view?r=eyJrIjoiMmUwZDY2MTAtNDdhYS00YTAzLWE0MGMtODljNDdlN2MxYjcwIiwidCI6ImNmY2M3N2NlLWQxYzctNDI5OS05YWRmLTRkZWJmNmM5NTJhNCIsImMiOjl9"></iframe>
        <p>Description of project 1 goes here... </p>
        </div>
    </main>
    <footer>
      <p>&copy; 2023 Sergio Molina</p>
    </footer>
  </body>
</html>
