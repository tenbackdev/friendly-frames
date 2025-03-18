**Product Requirements Document (PRD) - Friendly Frames**

**1. Overview**
The Friendly Frames app is a web-based application designed for casual and competitive bowlers to track scores, win-loss records, and performance metrics such as strike count. The app will prioritize a mobile-friendly experience while supporting larger screen resolutions.

**2. Objectives**
- Provide an intuitive interface for users to log and track their bowling scores.
- Enable friendly competition with win/loss tracking based on total scores and strike count.
- Ensure a mobile-first responsive design for accessibility across all devices.
- Offer historical performance insights and trends.
- Support multiple game modes, starting with single games. A "series" will be defined as a set of games played on a given day, with tracking of the specific day for historical records. Tournament-style competition may be added in future updates.

**3. Key Features**

**3.1 Player Scope & Data Access**
- The application will initially support only two players: Andy and Patrick.
- No user authentication is required; all data will be publicly accessible.
- Score tracking, win/loss records, and statistics will be visible to all users.

**3.2 Score Tracking & Game Management**
- Input game results by final score, strike count, spare count, open frame count, and split count.
- Automatic calculation of additional statistics based on provided data.
- Support for individual and series-based games.
- Display of game statistics, including strike/spare percentage.

**3.3 Competitive Features**
- Head-to-head win/loss tracking by total score and strike count, with additional breakdowns by individual game, daily results, and cumulative totals over time. Users may also define custom time frames for tracking win/loss records.
- Leaderboards exclusive to Andy and Patrick.
- Challenges and achievements for milestones (e.g., “Perfect Game,” “Turkey Streak”).

**3.4 Historical Data & Insights**
- View past games and progress over time.
- Graphical representation of trends in performance.
- Personalized insights and tips based on score history.



**3.6 Settings & Customization**
- Dark mode and theme selection.
- Adjustable scoring rules for different bowling formats.
- Notifications for game reminders and competition updates.

**4. Technical Requirements**
- Responsive web design optimized for mobile but adaptable to desktops.
- Backend will utilize a Google Sheets database, open to anyone with the link.
- Frontend will be developed using React.
- Real-time game updates will be maintained using WebSockets or similar live data synchronization methods.

**5. Non-Functional Requirements**
- High availability with 99.9% uptime.
- Secure data storage and encryption for user information.
- Fast load times (<2 seconds for most interactions).
- Accessibility compliance (WCAG 2.1 AA).

**6. Timeline & Milestones**
- Week 1-2: UI/UX Design and Wireframes.
- Week 3-4: Backend Development (Database, APIs).
- Week 5-6: Frontend Implementation.
- Week 7-8: Testing (Unit, Integration, User Testing).
- Week 9: Deployment and Beta Release.

**7. Success Metrics**
- Number of games tracked per user.
- Engagement in friendly competitions.
- Average response time for actions within the app.

**8. Risks & Mitigation**
- **User adoption**: Ensure a simple, intuitive interface.
- **Data loss**: Use cloud backups and redundancy.
- **Performance issues**: Optimize queries and caching strategies.

---

This PRD lays the foundation for developing Friendly Frames, a mobile-first bowling competition tracker that enhances user engagement and friendly competition while ensuring a seamless user experience across devices.

