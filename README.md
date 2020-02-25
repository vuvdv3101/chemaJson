# chemaJson

StoryModel {
  id: 1,
  category: [CategoryModel],
  title: String,
  followerCount: 40,
  follow: [User]
  viewer: 12030,
  chap: 10,
  updateTime: 24/02/2020 10:20,
  author: String,
  description: String,
  chapters: [ChapterModel]
  type: Manga or Novel
  vote: 4.5
  thumbnail: String,
  comment: [CommentModel]
}

//
CommentModel {
    id: 1,
    content: String,
    author: User,

}

//
ChapterModel {
  id: 1,
  type: Manga or Novel,
  title: String,
  content: String,
  
}

//
CategoryModel {
  id: 1,
  name: "action"
}

//
User {
    id: 1,
    avatar: String,
    username: String,
    email: String,
    tokenSNS: String,
    level: 1
    vip: true
}
