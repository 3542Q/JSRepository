存储文章的表
字段如下，分别为ID，标题，标题图片URL，内容URL
-- 文章表
CREATE TABLE Article (
    articleID INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255),
    titleImageURL TEXT,
    contentURL TEXT,
);
