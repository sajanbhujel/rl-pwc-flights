# RL-PWC dropout flights

Interactive page with real Crazyflie 2.1 Brushless flights through a 2 s position dropout (Lighthouse withheld from the estimator, standing in for GPS).

Each row shows one flight: the video, the measured path, and the distance from the moving setpoint, for EKF + PID, LSTM only, and RL-PWC (LSTM drift prediction with an RL-scaled waypoint shift).

Open `index.html`, or view the hosted page through GitHub Pages.
