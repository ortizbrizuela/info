<style>
  /* Global Styles */
  body {
    background-color: white; /* Entire page white */
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    color: black; /* Default text color */
  }

  /* Floating Sidebar */
  .sidebar {
    width: 300px;
    background: white; /* White background */
    color: black; /* Black text */
    position: fixed;
    top: 50%;
    left: 20px;
    transform: translateY(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    text-align: center;
    border-radius: 15px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2); /* Subtle shadow */
    transition: 0.3s ease-in-out;
  }

  /* Sidebar Image */
  .sidebar img {
    width: 120px;
    height: auto;
    border-radius: 50%;
    border: 3px solid black;
    margin-bottom: 15px;
  }

  /* Sidebar Hover Effect */
  .sidebar:hover {
    background: #f5f5f5; /* Slight hover change */
  }

  /* Main Content */
  .main-content {
    margin-left: 320px;
    padding: 20px;
    width: calc(100% - 340px);
  }

  .content {
    background: white;
    padding: 20px;
    max-width: 1000px;
    margin: auto;
    border-radius: 10px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    color: black;
  }

  /* Language Toggle Buttons */
  .language-toggle {
    text-align: center;
    margin-bottom: 20px;
  }

  .language-toggle button {
    background-color: #0073e6;
    color: white;
    border: none;
    padding: 10px 15px;
    font-size: 14px;
    cursor: pointer;
    border-radius: 5px;
    transition: background 0.3s ease-in-out;
    margin-left: 10px;
  }

  .language-toggle button:hover {
    background-color: #005bb5;
  }

  /* Hide one language version by default */
  .hidden {
    display: none;
  }

  /* Responsive Design */
  @media (max-width: 800px) {
    .sidebar {
      width: 80px;
      left: 10px;
      padding: 10px;
    }

    .sidebar img {
      width: 60px;
    }

    .sidebar h2, .sidebar p {
      display: none;
    }

    .main-content {
      margin-left: 100px;
      width: calc(100% - 120px);
    }
  }
</style>
