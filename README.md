<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FastSend - Secure Large File Transfers | Send Files Up to 10GB Free</title>
    <meta name="description" content="FastSend lets you securely transfer large files up to 10GB for free. No registration required. Perfect alternative when email attachments won't work.">
    <meta name="keywords" content="large file transfer, send big files, free file sharing, email attachments alternative, secure file transfer">
    <meta name="author" content="FastSend">
    <meta property="og:title" content="FastSend - Secure Large File Transfers">
    <meta property="og:description" content="Send files up to 10GB quickly and securely without registration">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://fastsend.example.com">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://fastsend.example.com">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_ID" crossorigin="anonymous"></script>
    <style>
        :root {
            --primary: #4361ee;
            --primary-light: #4895ef;
            --secondary: #3f37c9;
            --accent: #f72585;
            --dark: #1a1a2e;
            --light: #f8f9fa;
            --gray: #6c757d;
            --success: #4cc9f0;
            --warning: #f8961e;
            --danger: #ef233c;
            --border-radius: 12px;
            --box-shadow: 0 8px 30px rgba(0, 0, 0, 0.12);
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: #f5f7ff;
            min-height: 100vh;
        }

        /* Header */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
            position: sticky;
            top: 0;
            z-index: 100;
            padding: 1rem 0;
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1.5rem;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary);
            text-decoration: none;
        }

        .nav-links {
            display: flex;
            gap: 1.5rem;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--gray);
            font-weight: 500;
            transition: var(--transition);
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        /* Main Content */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        /* Ad Containers */
        .ad-container {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 1rem;
            margin: 2rem 0;
            text-align: center;
            min-height: 90px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Home Page */
        .hero {
            text-align: center;
            padding: 2rem 0 4rem;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--dark);
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--gray);
            max-width: 700px;
            margin: 0 auto 2rem;
        }

        /* Transfer Form */
        .transfer-card {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 2rem;
            margin-bottom: 3rem;
        }

        /* Form Styles */
        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--dark);
        }

        .form-control {
            width: 100%;
            padding: 0.875rem 1rem;
            border: 1px solid #e0e0e0;
            border-radius: var(--border-radius);
            font-size: 1rem;
            transition: var(--transition);
        }

        .form-control:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(67, 97, 238, 0.2);
        }

        textarea.form-control {
            min-height: 120px;
            resize: vertical;
        }

        /* File Upload */
        .file-upload {
            border: 2px dashed #e0e0e0;
            border-radius: var(--border-radius);
            padding: 3rem 2rem;
            text-align: center;
            cursor: pointer;
            transition: var(--transition);
        }

        .file-upload:hover {
            border-color: var(--primary);
            background-color: rgba(67, 97, 238, 0.05);
        }

        .file-upload i {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 1rem;
        }

        .file-upload p {
            color: var(--gray);
        }

        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 3rem 0;
            margin-top: 3rem;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            padding: 0 1.5rem;
        }

        .footer-column h3 {
            color: white;
            margin-bottom: 1.5rem;
            font-size: 1.2rem;
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 0.8rem;
        }

        .footer-links a {
            color: #bdc1c6;
            text-decoration: none;
            transition: var(--transition);
        }

        .footer-links a:hover {
            color: white;
        }

        .copyright {
            text-align: center;
            margin-top: 2rem;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #bdc1c6;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                gap: 1rem;
            }
            
            .nav-links {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Structured Data for SEO -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebApplication",
      "name": "FastSend",
      "url": "https://fastsend.example.com",
      "description": "Secure large file transfer service for sending files up to 10GB",
      "applicationCategory": "FileTransfer",
      "operatingSystem": "Web"
    }
    </script>

    <header>
        <nav class="navbar">
            <a href="#" class="logo">
                <i class="fas fa-paper-plane"></i>
                <span>FastSend</span>
            </a>
            <div class="nav-links">
                <a href="#">Home</a>
                <a href="#">How It Works</a>
                <a href="#">Pricing</a>
                <a href="#">Help</a>
            </div>
        </nav>
    </header>

    <main class="container">
        <!-- Top Ad Unit -->
        <div class="ad-container">
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                data-ad-slot="YOUR_TOP_AD_SLOT"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>

        <section class="hero">
            <h1>Send Large Files Easily, No Account Needed</h1>
            <p>Transfer files up to 10GB for free. Fast, secure, and simple - perfect when email attachments won't work.</p>
        </section>

        <div class="transfer-card">
            <h2>Send a File</h2>
            <form id="fileTransferForm">
                <div class="form-group">
                    <label for="senderEmail">Your Email</label>
                    <input type="email" id="senderEmail" class="form-control" placeholder="Enter your email address" required>
                </div>
                
                <div class="form-group">
                    <label for="recipientEmail">Recipient's Email</label>
                    <input type="email" id="recipientEmail" class="form-control" placeholder="Enter recipient's email address" required>
                </div>
                
                <div class="form-group">
                    <label for="message">Message (Optional)</label>
                    <textarea id="message" class="form-control" placeholder="Add a message to your recipient"></textarea>
                </div>
                
                <div class="form-group">
                    <label>File to Send</label>
                    <div class="file-upload" id="fileUploadArea">
                        <i class="fas fa-cloud-upload-alt"></i>
                        <p>Click to browse or drag and drop your files here</p>
                        <input type="file" id="fileInput" style="display: none;" required>
                    </div>
                </div>
                
                <button type="submit" style="background-color: var(--primary); color: white; padding: 0.8rem 1.5rem; border: none; border-radius: var(--border-radius); font-size: 1rem; font-weight: 600; cursor: pointer; width: 100%; transition: var(--transition);">
                    <i class="fas fa-paper-plane"></i> Send File Now
                </button>
            </form>
        </div>

        <!-- Middle Ad Unit -->
        <div class="ad-container">
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                data-ad-slot="YOUR_MIDDLE_AD_SLOT"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>

        <section style="margin: 3rem 0;">
            <h2 style="text-align: center; margin-bottom: 2rem;">Why Choose FastSend?</h2>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem;">
                <div style="background-color: white; border-radius: var(--border-radius); box-shadow: var(--box-shadow); padding: 2rem; text-align: center;">
                    <i class="fas fa-bolt" style="font-size: 2.5rem; color: var(--primary); margin-bottom: 1.5rem;"></i>
                    <h3 style="margin-bottom: 1rem;">Lightning Fast</h3>
                    <p style="color: var(--gray);">Our optimized servers ensure your files transfer as quickly as possible.</p>
                </div>
                
                <div style="background-color: white; border-radius: var(--border-radius); box-shadow: var(--box-shadow); padding: 2rem; text-align: center;">
                    <i class="fas fa-shield-alt" style="font-size: 2.5rem; color: var(--primary); margin-bottom: 1.5rem;"></i>
                    <h3 style="margin-bottom: 1rem;">Secure Transfers</h3>
                    <p style="color: var(--gray);">All files are encrypted during transfer and automatically deleted.</p>
                </div>
                
                <div style="background-color: white; border-radius: var(--border-radius); box-shadow: var(--box-shadow); padding: 2rem; text-align: center;">
                    <i class="fas fa-globe" style="font-size: 2.5rem; color: var(--primary); margin-bottom: 1.5rem;"></i>
                    <h3 style="margin-bottom: 1rem;">Worldwide Access</h3>
                    <p style="color: var(--gray);">Send files to anyone, anywhere with our global network.</p>
                </div>
            </div>
        </section>

        <!-- Bottom Ad Unit -->
        <div class="ad-container">
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                data-ad-slot="YOUR_BOTTOM_AD_SLOT"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </main>

    <footer>
        <div class="footer-content">
            <div class="footer-column">
                <h3>FastSend</h3>
                <ul class="footer-links">
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">Press</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h3>Features</h3>
                <ul class="footer-links">
                    <li><a href="#">Large File Transfer</a></li>
                    <li><a href="#">Secure Sharing</a></li>
                    <li><a href="#">No Registration</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h3>Help</h3>
                <ul class="footer-links">
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Contact Support</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h3>Connect</h3>
                <ul class="footer-links">
                    <li><a href="#"><i class="fab fa-twitter"></i> Twitter</a></li>
                    <li><a href="#"><i class="fab fa-facebook"></i> Facebook</a></li>
                    <li><a href="#"><i class="fab fa-instagram"></i> Instagram</a></li>
                </ul>
            </div>
        </div>
        
        <div class="copyright">
            <p>&copy; 2023 FastSend. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // File upload functionality
        const fileUploadArea = document.getElementById('fileUploadArea');
        const fileInput = document.getElementById('fileInput');
        
        fileUploadArea.addEventListener('click', () => fileInput.click());
        
        fileUploadArea.addEventListener('dragover', (e) => {
            e.preventDefault();
            fileUploadArea.style.borderColor = 'var(--primary)';
            fileUploadArea.style.backgroundColor = 'rgba(67, 97, 238, 0.05)';
        });
        
        fileUploadArea.addEventListener('dragleave', () => {
            fileUploadArea.style.borderColor = '#e0e0e0';
            fileUploadArea.style.backgroundColor = 'white';
        });
        
        fileUploadArea.addEventListener('drop', (e) => {
            e.preventDefault();
            fileUploadArea.style.borderColor = '#e0e0e0';
            fileUploadArea.style.backgroundColor = 'white';
            
            if (e.dataTransfer.files.length) {
                fileInput.files = e.dataTransfer.files;
                updateFileInfo();
            }
        });
        
        fileInput.addEventListener('change', updateFileInfo);
        
        function updateFileInfo() {
            if (fileInput.files.length > 0) {
                const file = fileInput.files[0];
                fileUploadArea.innerHTML = `
                    <i class="fas fa-file-alt" style="font-size: 3rem; color: var(--primary); margin-bottom: 1rem;"></i>
                    <p style="font-weight: 600; margin-bottom: 0.5rem;">${file.name}</p>
                    <p style="color: var(--gray);">${formatFileSize(file.size)}</p>
                    <button onclick="clearFile()" style="background: none; border: none; color: var(--primary); cursor: pointer; margin-top: 1rem;">
                        <i class="fas fa-times"></i> Change file
                    </button>
                `;
            }
        }
        
        function clearFile() {
            fileInput.value = '';
            fileUploadArea.innerHTML = `
                <i class="fas fa-cloud-upload-alt"></i>
                <p>Click to browse or drag and drop your files here</p>
            `;
        }
        
        function formatFileSize(bytes) {
            if (bytes === 0) return '0 Bytes';
            const k = 1024;
            const sizes = ['Bytes', 'KB', 'MB', 'GB', 'TB'];
            const i = Math.floor(Math.log(bytes) / Math.log(k));
            return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
        }
        
        // Form submission
        document.getElementById('fileTransferForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('File upload simulated. In a real implementation, this would upload the file to your server.');
        });
    </script>
</body>
</html>
