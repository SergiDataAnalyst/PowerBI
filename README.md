# Projects

On this page, you can explore a collection of the Power BI dashboards that I have personally crafted. Each dashboard serves as a testament to my data visualization expertise and showcases my dedication to delivering top-notch, intuitive, and insightful data-driven solutions. Please feel free to browse through my portfolio and witness the power of visually appealing and interactive dashboards.


<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Dashboard Showcase</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <style>
      body {
        font-family: 'Segoe UI', sans-serif;
        margin: 0;
        padding: 0;
        background-color: #F9F9F9;
      }
      .dashboard-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
      .dashboard {
        margin: 30px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        overflow: hidden;
        border-radius: 5px;
      }
      .dashboard-header {
        background-color: #0078D4;
        color: white;
        font-size: 28px;
        font-weight: 600;
        padding: 20px;
        text-align: center;
        transition: all 0.2s;
      }
      .dashboard-header:hover {
        background-color: #106EBE;
        cursor: pointer;
      }
      .dashboard-content {
        position: relative;
        width: 100%;
        padding-bottom: 62.5%;
        height: 0;
        overflow: hidden;
      }
      .dashboard-iframe {
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        border: none;
      }
    </style>
  </head>
  <body>
    <div class="dashboard-container">
      <div class="dashboard">
        <div class="dashboard-header">
          <h2>Netflix TV Shows and Movies Stats by Country</h2>
          <p>Click to expand</p>
        </div>
        <div class="dashboard-content">
          <iframe class="dashboard-iframe" title="Netflix" src="https://app.powerbi.com/view?r=eyJrIjoiMmUwZDY2MTAtNDdhYS00YTAzLWE0MGMtODljNDdlN2MxYjcwIiwidCI6ImNmY2M3N2NlLWQxYzctNDI5OS05YWRmLTRkZWJmNmM5NTJhNCIsImMiOjl9" frameborder="0" allowFullScreen="true"></iframe>
        </div>
      </div>
      <div class="dashboard">
        <div class="dashboard-header">
          <h2>Power BI YouTube Channels with the Most Views</h2>
          <p>Click to expand</p>
        </div>
        <div class="dashboard-content">
          <iframe class="dashboard-iframe" title="Power BI YouTube" src="https://app.powerbi.com/view?r=eyJrIjoiZGJjYjdjN2UtZTczMy00OWJlLTg2NTYtOTU2YzkyY2JkYzMxIiwidCI6ImZhNmYyNWVmLTlhMTMtNGYxNi05OTViLWUyMzYwNGJhZmUzMCJ9" frameborder="0" allowFullScreen="true"></iframe>
        </div>
      </div>
      <div class="dashboard">
        <div class="dashboard-header">
          <h2>YouTube Analytics</h2>
            <p>This Power BI dashboard provides an analysis of YouTube channel performance, including engagement metrics, audience demographics, and video statistics.</p>
          </div>
          <iframe class="powerbi-iframe" title="YouTube Analytics" width="800" height="498" src="https://app.powerbi.com/view?r=eyJrIjoiMjVjYmUzZGMtOWZlYS00ZjYwLWI2ZmMtNDI2ZTE5NTY0ZTk4IiwidCI6Ijg3N2EzOTlkLWY4NzktNDU4MS1iMzE3LWNiYzYxNDkyODA3NSIsImMiOjR9" frameborder="0" allowFullScreen="true"></iframe>
        </div>
      </div>
    </div>
  </body>
</html>
<style>
  body {
    background-color: #f5f5f5;
  }
  .dashboard {
    margin: 0 auto;
    max-width: 800px;
    background-color: #ffffff;
    box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.15);
    border-radius: 4px;
    padding: 20px;
    margin-bottom: 40px;
  }
  .dashboard-header {
    text-align: center;
    margin-bottom: 20px;
  }
  .dashboard-header h2 {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 10px;
  }
  .dashboard-header p {
    font-size: 16px;
    color: #666666;
    line-height: 24px;
  }
  .powerbi-iframe {
    width: 100%;
    height: 100%;
  }
</style>
</head>
<body>
  <div class="dashboard">
    <div class="dashboard-header">
      <h2>YouTube Analytics</h2>
      <p>This Power BI dashboard provides an analysis of YouTube channel performance, including engagement metrics, audience demographics, and video statistics.</p>
    </div>
    <div class="dashboard-container">
      <iframe class="powerbi-iframe" title="YouTube Analytics" width="800" height="498" src="https://app.powerbi.com/view?r=eyJrIjoiMjVjYmUzZGMtOWZlYS00ZjYwLWI2ZmMtNDI2ZTE5NTY0ZTk4IiwidCI6Ijg3N2EzOTlkLWY4NzktNDU4MS1iMzE3LWNiYzYxNDkyODA3NSIsImMiOjR9" frameborder="0" allowFullScreen="true"></iframe>
    </div>
  </div>
  <script>
    // Add interactivity here
  </script>
</body>
</html>


