# sarrix-release-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarrix Release Submission Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #121212;
            color: white;
        }
        .container {
            max-width: 500px;
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255,255,255,0.1);
        }
        label {
            font-weight: bold;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #444;
            border-radius: 5px;
            background: #333;
            color: white;
        }
        button {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #218838;
        }
        .logo {
            display: block;
            margin: 0 auto 20px;
            width: 100px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="/mnt/data/Strixx 4000.jpg" alt="Sarrix Logo" class="logo">
        <h2>Sarrix Release Submission Form</h2>
        <form action="#" method="POST" enctype="multipart/form-data">
            <label for="artist_name">Artist Name:</label>
            <input type="text" id="artist_name" name="artist_name" required>
            
            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="song_title">Song Title:</label>
            <input type="text" id="song_title" name="song_title" required>
            
            <label for="genre">Genre:</label>
            <input type="text" id="genre" name="genre" required>
            
            <label for="demo_upload">Upload Demo (MP3, WAV, or Link):</label>
            <input type="file" id="demo_upload" name="demo_upload" accept="audio/*">
            
            <label for="image_upload">Upload Cover Image:</label>
            <input type="file" id="image_upload" name="image_upload" accept="image/*">
            
            <label for="lyrics">Lyrics (Optional):</label>
            <textarea id="lyrics" name="lyrics" rows="4"></textarea>
            
            <label for="copyright">Copyright Status:</label>
            <select id="copyright" name="copyright">
                <option value="nocopyright">No Copyright</option>
                <option value="copyright">Copyrighted</option>
            </select>
            
            <label for="label">Choose Label:</label>
            <select id="label" name="label">
                <option value="regroups_records">Regroups Records</option>
                <option value="snbbm_records">SNBBM Records</option>
                <option value="sarrix_music">Sarrix Music (Copyright-Free Music)</option>
            </select>
            
            <label for="label_comments">Other Comments (About Choosing Labels):</label>
            <textarea id="label_comments" name="label_comments" rows="4"></textarea>
            
            <label for="social_links">Social Media Links:</label>
            <input type="text" id="social_links" name="social_links">
            
            <label for="message">Message (Tell us about your music):</label>
            <textarea id="message" name="message" rows="4"></textarea>
            
            <button type="submit">Submit Demo</button>
        </form>
    </div>
</body>
</html>
