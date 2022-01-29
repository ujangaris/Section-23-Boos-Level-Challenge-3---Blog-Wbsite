## 275. Seting Up the Blog Project

    npm install

## Home Page

pada browser: http://localhost:3000/

## About, Contact, and Compose

pada browser: - http://localhost:3000/about - http://localhost:3000/contact - http://localhost:3000/compose

## Menampilkan hasil inputan pada terminal

    - http://localhost:3000/compose
    input kata sembarang kemudian liat pada terminal , jika berhasil akan ada output sesuai yang di input pada browser

## Form Input dengan Bootstrap

    Documentation:
                    - https://getbootstrap.com/docs/4.0/components/forms/
                    - https://www.w3schools.com/tags/tag_textarea.asp


    - http://localhost:3000/posts/Test
    input title : Test, Content: lorem.... liat pada terminal , jika berhasil akan ada output sesuai yang di input pada browser

## Slug dengan loadsh , Single page

    Documentation:
                    - https://lodash.com/
                    - https://lodash.com/docs/4.17.15#lowerCase

    - http://localhost:3000/compose
    input title : Another post, Content: lorem....

    liat pada browser:
    - http://localhost:3000/posts/another-post

    maka akan ada single post

## Truncate string javascript (substring)

    Documentation:
                    - https://stackoverflow.com/questions/1301512/truncate-a-string-straight-javascript
                    - https://www.w3schools.com/jsref/jsref_substring.asp

    - http://localhost:3000/compose
    input title : Another post

    Content: Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

    liat pada browser:
    - http://localhost:3000
    akan terlihat pada content post yang baru saja dibuat akan terbatasi menjadi 100 character:
        Another post
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the ...
