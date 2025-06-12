# JMeter Performance Testing Project (Learning Phase)

This project contains a JMeter Test Plan designed to simulate different performance testing scenarios.  
It includes multiple Thread Groups within a single `.jmx` file to represent the following tests:

## 🧪 Test Scenarios Included
1. **Basic Load Test**  
   - Threads: 10 | Ramp-Up: 5 sec | Loop Count: 2 | Timer: 1000 ms  
   - Validates basic performance under low user load.

2. **Moderate Load Test**  
   - Threads: 50 | Ramp-Up: 10 sec | Loop Count: 5 | Timer: 2000 ms  
   - Simulates regular business traffic.

3. **Stress Test**  
   - Threads: 100 | Ramp-Up: 5 sec | Loop Count: 1 | Timer: 500 ms  
   - Tests system under peak load conditions.

4. **Soak Test**  
   - Threads: 20 | Ramp-Up: 10 sec | Loop Count: 100 | Timer: 3000 ms  
   - Checks for memory leaks and stability over time.

5. **Spike Test**  
   - Threads: 200 | Ramp-Up: 1 sec | Loop Count: 1 | Timer: 500 ms  
   - Tests system reaction to a sudden traffic spike.

## 📂 Project Structure
- `PerformanceTestingPlan.jmx` – Main JMeter test plan with all test scenarios
- `Results/` – Contains output result files

## 📌 Notes
- Created as part of my **learning phase in Performance Testing**.
- Metrics analyzed: Response Time, Throughput, Error %, Peak Load behavior.

## 🔗 Tools Used
- Apache JMeter
- Aggregate Report listeners

## 👨‍💻 Author
Gaurav Prakash Pagar
