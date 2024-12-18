# Performance Testing with K6
[![JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Grafana](https://img.shields.io/badge/Monitoring-Grafana-F46800.svg)](https://grafana.com/)
[![k6](https://img.shields.io/badge/Load%20Testing-k6-2E8BC0.svg)](https://k6.io/)
[![Prometheus](https://img.shields.io/badge/Monitoring-Prometheus-E6522C.svg)](https://prometheus.io/)

### This is a test project for **Back-End Test Automation** March 2024 Course @ SoftUni

---

## About
This project demonstrates different types of Performance Testing with K6.

## Types of Performance Tests Covered
- **Smoke Testing:** Quick tests to check the basic functionality of the application.
- **Load Testing:** Evaluates how the system behaves under expected load conditions.
- **Stress Testing:** Determines the system's robustness by testing beyond normal operational capacity.
- **Spike Testing:** Assesses system performance under sudden, sharp increases in load.
- **Soak (Endurance) Testing:** Tests the system's stability and performance over an extended period.
- **Breakpoint Testing:** Identifies the point at which the system fails or its performance degrades significantly.

## 📊 Grafana for Monitoring
Grafana is used for real-time monitoring and visualization of performance test results.

##  Setting Up Grafana
1. **Install Grafana:** Download and install Grafana from the [official site](https://grafana.com/).
2. **Set Up Dashboards:**
   - Create a new dashboard and add panels for metrics like response time, throughput, and error rate.
   - Connect to data sources like Prometheus or k6 Cloud for real-time data.
3. **Integration with k6:**
   - Export metrics from k6 to Grafana by configuring output plugins like `--out influxdb` or `--out prometheus`.

## ☁️ Grafana Cloud
If you prefer a hosted solution, Grafana Cloud provides easy setup and integration with k6.  
- **Sign Up:** Register for a Grafana Cloud account [here](https://grafana.com/products/cloud/).
- **Connect to k6:** Link your k6 metrics to Grafana Cloud for live visualization.

## k6 Cloud
k6 Cloud simplifies running performance tests and provides detailed reports.

## Setting Up k6 Cloud
1. **Create a Grafana Cloud account:**
   - Use an existing account or register at [Grafana Cloud](https://grafana.com/products/cloud/).
2. **Navigate to k6 Cloud:**
   - After registration, access the k6 Cloud section at [k6 Cloud](https://grafana.com/products/k6-cloud/).

## Running Tests on k6 Cloud
1. **Log in to k6 Cloud:**
   - Use the k6 CLI to connect to your account with an API token.
   ```sh
   k6 login cloud --token {your-token}

## Monitoring Test Results
- View metrics like latency, throughput, and error rates in real time on Grafana dashboards.  
- Analyze trends and identify performance bottlenecks using Grafana's visualization tools.

## Further Studies
- [Official k6 YouTube channel](https://www.youtube.com/c/k6test)  
- [Official k6 Documentation](https://grafana.com/docs/k6/latest/)  
- [Grafana Documentation](https://grafana.com/docs/)

## License
This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

---

## Happy Testing! 🚀

