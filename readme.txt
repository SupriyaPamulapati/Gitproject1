ConfigurationBuilder cb = new ConfigurationBuilder();
    cb.setDebugEnabled(true)
    .setOAuthConsumerKey("SaZHlQid1ZgIuuU6cYgwl8NkmgZc1tO0U977rGYxSlCYDPvbdQ")
    .setOAuthConsumerSecret("SaZHlQid1ZgIuuU6cYgwl8NkmgZc1tO0U977rGYxSlCYDPvbdQ")
    .setOAuthAccessToken("1450686116353376256-0bN9L1fBR2Jef6Vn6lMgbgEM3sRdwY")
    .setOAuthAccessTokenSecret("0XtsY9PJ44EtOmDucolXxnHegRzYeHDErb3IlQeg2zaQ5");
    TwitterFactory tf = new TwitterFactory(cb.build());
    Twitter twitter = tf.getInstance();



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