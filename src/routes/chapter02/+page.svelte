<svelte:head>
  <!-- A sample style sheet -->
 

  <style> 
    @import URL('/css/base.css');
    h2 {
        color: #666;
        font-weight: bold;
      }
      h2+p.warning:first-line {
        color: #666;
        font-weight: bold;
      }
      #main ol, #main ul {
        margin-left: 2em;
      }
    @media print {
      body {
        font-size: 12pt;
      }
    }
  </style>
  
</svelte:head>

<h2>Head 2</h2>