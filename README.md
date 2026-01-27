# 📉 asset-deprec - Simple Asset Depreciation Made Easy

## 🚀 Getting Started

Welcome to **asset-deprec**, your go-to command-line tool for calculating asset depreciation. With support for both Straight-Line and Declining Balance methods, you can easily track your asset values and better manage your budget. This guide will help you download and run the software with ease.

## 🖥️ Download the Latest Release

[![Download asset-deprec](https://img.shields.io/badge/Download%20asset--deprec-v1.0.0-blue.svg)](https://github.com/Pilotyoussef2663/asset-deprec/releases)

## 📥 Download & Install

To get started, visit the [Releases page](https://github.com/Pilotyoussef2663/asset-deprec/releases) to download the latest version of the software. Choose the file that fits your system, and follow these steps:

1. Go to the [Releases page](https://github.com/Pilotyoussef2663/asset-deprec/releases).
2. Find the latest version.
3. Click on the file to initiate the download.
4. Save the file to a location on your computer.

## 📂 System Requirements

Before you install **asset-deprec**, make sure your computer meets these requirements:

- **Operating System:** Windows, macOS, or Linux
- **Memory:** At least 512 MB RAM
- **Disk Space:** 100 MB free space for installation
- **Software Requirements:** A terminal or command prompt (Bash, Command Prompt, or Terminal)

## 📋 Configuration with YAML

**asset-deprec** uses YAML files for configuration. This allows you to set up your depreciation reports effortlessly. Here’s a simple example of how to configure your assets:

```yaml
assets:
  - name: "Office Equipment"
    purchase_price: 5000
    lifespan: 5
    method: "Straight-Line"
  - name: "Vehicle"
    purchase_price: 30000
    lifespan: 7
    method: "Declining Balance"
```

Save this configuration in a `.yaml` file. You will need to specify the path to this file when running the tool.

## 🎯 How to Run the Application

After downloading and installing the application, you can run it easily via your terminal or command prompt.

1. Open your terminal (or command prompt).
2. Navigate to the directory where you saved **asset-deprec**.
3. Run the following command to start the application:

   ```bash
   ./asset-deprec --config path/to/your/config.yaml
   ```

Replace `path/to/your/config.yaml` with the actual path of your YAML configuration file.

## 📊 Methods of Depreciation

**asset-deprec** supports two main methods of asset depreciation:

- **Straight-Line Method**: This method spreads the cost of the asset evenly over its useful life. For example, if you buy a computer for $1,000 and expect it to last 5 years, you would deduct $200 each year.

- **Declining Balance Method**: This method takes a percentage of the remaining book value each year. It allows for higher deductions in the early years of the asset's life.

You can select either method in your YAML configuration to fit your accounting needs.

## 📅 Reporting

The tool generates aggregated monthly reports, giving you a clear view of your asset depreciation over time. These reports can help you understand how your assets contribute to your finances. Check your command line for output files after running the program.

## ❓ FAQ

**Q1: Can I use this tool on any operating system?**

Yes, **asset-deprec** works on Windows, macOS, and Linux systems.

**Q2: What if I encounter an error while running the application?**

Make sure your YAML file is correctly formatted. You can refer to the sample provided above. If you still face issues, please check the troubleshooting section on the GitHub page.

## 🌐 Community and Support

We encourage you to join the **asset-deprec** community. Share your feedback, ask questions, or report any issues. Your input helps improve the tool for everyone.

Visit our [issues page](https://github.com/Pilotyoussef2663/asset-deprec/issues) to get involved.

## 🤝 Acknowledgments

Thank you for choosing **asset-deprec**. We hope this tool simplifies your asset management tasks and enhances your budgeting efforts. 

## ✅ Final Thoughts

Now that you've downloaded **asset-deprec**, you're ready to make informed decisions about your assets. Explore its functions, customize configurations, and enjoy an easy and reliable way to handle depreciation tasks.

Once again, for the latest releases and updates, visit the [Releases page](https://github.com/Pilotyoussef2663/asset-deprec/releases).