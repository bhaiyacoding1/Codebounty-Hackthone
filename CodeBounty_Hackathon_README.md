
# CodeBounty Hackathon

Welcome to the **CodeBounty Hackathon** repository! This project is aimed at organizing an online and offline hackathon themed around **AI and Web Development** for college students. 

### Features:
- **Team Registration**: Participants can register teams of 2 to 4 members.
- **Admin Panel**: Admins can view team registration data, filter teams, and mark teams for the second round.
- **Team Dashboard**: Teams can view their progress, round 1 status, and notifications.
- **Email Notifications**: Automatic emails for registration, and when teams qualify for round 2.

### Project Setup

To run this project locally, follow the steps below:

#### 1. **Clone the Repository:**

```bash
git clone https://github.com/bhaiyacoding1/Codebounty-Hackthone.git
```

#### 2. **Install Dependencies:**

Navigate to the project folder:

```bash
cd Codebounty-Hackthone
```

Then install the necessary dependencies using:

```bash
npm install
```

#### 3. **Set Up Firebase:**

- Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
- Set up **Firestore**, **Authentication**, and **Firebase Hosting**.
- Update your **Firebase configuration** in the project (`firebaseConfig.js`).

#### 4. **Run Locally:**

To run the project on your local server, use:

```bash
npm start
```

This will start the project locally on `http://localhost:3000`.

### Vercel Deployment

You can also deploy the project on Vercel for live use. Here’s how to set it up:
- Connect this GitHub repository to **Vercel**.
- Vercel will automatically deploy your site once connected.
- You'll receive a link like `https://your-project-name.vercel.app`.

### Features to Explore:

- **Admin Panel**: Admins can filter, view team data, and send notifications to teams qualifying for round 2.
- **Real-Time Registration**: Teams register via the website, and data is stored in Firebase for live tracking.

---

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
