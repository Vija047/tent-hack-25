# tent-hack-25
spree-app/
│
├── assets/                     # Static assets
│   ├── fonts/                  # Custom fonts
│   ├── images/                 # App images/icons
│   └── videos/                 # Exercise videos
│
├── src/
│   ├── api/                    # Backend API integration
│   │   ├── authApi.js
│   │   ├── exercisesApi.js
│   │   ├── notificationsApi.js
│   │   └── userApi.js
│   │
│   ├── components/             # Reusable UI components
│   │   ├── common/             # Buttons, Inputs, Cards, Modals
│   │   │   ├── Button.js
│   │   │   ├── Input.js
│   │   │   ├── Card.js
│   │   │   └── LoadingSpinner.js
│   │   ├── ExerciseItem.js
│   │   ├── CheerMessage.js
│   │   └── EmergencyButton.js
│   │
│   ├── hooks/                  # Custom React hooks
│   │   ├── useAuth.js
│   │   ├── useExercises.js
│   │   └── useNotifications.js
│   │
│   ├── navigation/             # Navigation stacks and tabs
│   │   ├── AppNavigator.js
│   │   ├── AuthNavigator.js
│   │   └── MainTabNavigator.js
│   │
│   ├── screens/                # Screen-level components
│   │   ├── auth/               # Authentication
│   │   │   ├── LoginScreen.js
│   │   │   ├── SignupScreen.js
│   │   │   ├── ForgotPasswordScreen.js
│   │   │   └── VerifyOTPScreen.js
│   │   │
│   │   ├── champion/           # Seniors
│   │   │   ├── HomeScreen.js
│   │   │   ├── ExerciseScreen.js
│   │   │   ├── ExerciseDetailScreen.js
│   │   │   ├── ProfileScreen.js
│   │   │   ├── NotificationsScreen.js
│   │   │   └── EmergencyScreen.js
│   │   │
│   │   ├── spotter/            # Caregivers
│   │   │   ├── DashboardScreen.js
│   │   │   ├── TrackProgressScreen.js
│   │   │   ├── GuideExerciseScreen.js
│   │   │   ├── AddSeniorScreen.js
│   │   │   └── ProfileScreen.js
│   │   │
│   │   ├── supporter/          # Family & friends
│   │   │   ├── CheerScreen.js
│   │   │   ├── MessagesScreen.js
│   │   │   ├── SeniorListScreen.js
│   │   │   └── ProfileScreen.js
│   │   │
│   │   ├── settings/           # App preferences
│   │   │   ├── LanguageScreen.js
│   │   │   ├── NotificationSettings.js
│   │   │   └── AccountSettings.js
│   │   │
│   │   └── onboarding/         # First-time setup
│   │       ├── WelcomeScreen.js
│   │       ├── TutorialScreen.js
│   │       └── PermissionsScreen.js
│   │
│   ├── store/                  # State management (Redux/Zustand)
│   │   ├── authSlice.js
│   │   ├── exerciseSlice.js
│   │   └── notificationSlice.js
│   │
│   ├── styles/                 # Global styles & themes
│   │   ├── colors.js
│   │   ├── fonts.js
│   │   └── globalStyles.js
│   │
│   ├── utils/                  # Utility functions
│   │   ├── helpers.js
│   │   └── validators.js
│   │
│   └── App.js                  # Root component
│
├── .env                        # Environment variables
├── package.json
├── babel.config.js
├── metro.config.js
└── README.md
<img width="1024" height="1024" alt="auth-img" src="https://github.com/user-attachments/assets/65f41bb2-4d6c-4bd0-b492-fcf86c970ae3" />

<img width="1024" height="1024" alt="compaion" src="https://github.com/user-attachments/assets/d4a442d0-01ec-4156-a1fe-e8b882192c15" />
<img width="1024" height="1024" alt="spotter" src="https://github.com/user-attachments/assets/a5ff1540-d735-4259-8f9c-d91967105795" />
<img width="1024" height="1024" alt="supptter" src="https://github.com/user-attachments/assets/5bcbe4ba-5b6c-4e32-aa71-0b88ef4c9e21" />


