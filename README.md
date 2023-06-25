# Twitter Clone
Backend: Spring
Frontend: Next.js
Stylling: Tailwind CSS
Database: MongoDB

## Spring
### Model classes
1. public class User {
    private String id;
    private String username;
    private String password;
    // Additional user attributes (e.g., name, bio, profile picture)
  }

1. public class Tweet {
    @Id
    private String id;
    private String content;
    private String userId;
    private LocalDateTime createdAt;
    // Additional tweet attributes (e.g., likes, retweets)
  }

3. 
