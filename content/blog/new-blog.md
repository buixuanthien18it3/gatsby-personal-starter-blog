---
path: https://github.com/buixuanthien18it3/gatsby-personal-starter-blog
date: 2021-01-01T08:49:41.312Z
title: My Blog IT
description: Đây là nguồn blog của mình
---
```js
return (
      <Wrapper>
        <div
          style={{
            marginLeft: `auto`,
            marginRight: `auto`,
            maxWidth: rhythm(24),
            padding: `${rhythm(1.5)} ${rhythm(3 / 4)}`,
          }}
        >
          <header>{header}</header>
          <main>{children}</main>
        </div>
        <Footer>
          © {new Date().getFullYear()}, Nhóm IT4A
          {` `}
          <a href="https://www.gatsbyjs.org"> Gatsby</a>
        </Footer>
      </Wrapper>
    )
```