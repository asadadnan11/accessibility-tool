# AI-Powered Interactive Learning Platform

## Overview

A comprehensive, client-side web application that transforms educational content into accessible, interactive learning materials. Built specifically for **ESL and neurodivergent students**, this platform leverages OpenAI's GPT and Whisper APIs to automatically generate flashcards, quizzes, summaries, and study guides from lecture transcripts.

## Key Features

### Core Functionality
- **Multi-Format Input**: Upload audio/video files, paste URLs, or input transcripts manually
- **AI-Powered Content Generation**: Automatic creation of study materials using OpenAI GPT-3.5
- **Real-time Transcription**: Audio processing with OpenAI Whisper API
- **Interactive Learning Tools**: Flashcards, quizzes, summaries, and study guides

### Accessibility Features
- **Visual Customization**: High contrast, dyslexia-friendly themes, adjustable font sizes
- **Audio Support**: Text-to-speech for all content with voice input capabilities
- **Focus Mode**: Distraction-free learning environment
- **Multilingual Support**: Content translation and voice input in multiple languages
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### Learning Optimization
- **Smart Content Parsing**: Intelligent flashcard generation with automatic Q&A detection
- **Progressive Learning**: Interactive quizzes with immediate feedback
- **Structured Study Materials**: Organized summaries and study guides
- **ESL-Friendly Content**: Simplified language and clear explanations

## Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- OpenAI API key (for AI features and transcription)

### Installation & Usage
1. **Download**: Clone or download this repository
2. **Open**: Load `complete_interactive_learning.html` in your browser
3. **Configure**: Enter your OpenAI API key in the designated field
4. **Input Content**: Choose your preferred input method:
   - **File Upload**: Upload audio (MP3, WAV) or video files
   - **URL Input**: Paste direct video URLs
   - **Manual Entry**: Copy-paste your transcript text
5. **Generate Materials**: Use the AI buttons to create flashcards, quizzes, and summaries
6. **Customize**: Adjust accessibility settings and themes as needed

## Input Methods

### Audio/Video Processing
- **Supported Formats**: MP3, WAV, MP4, MOV, AVI
- **Processing**: Automatic transcription using OpenAI Whisper API
- **Limitations**: Video files require audio extraction (handled automatically)

### Manual Transcript Input
- **Direct Entry**: Paste any transcript text directly
- **Format Flexibility**: Accepts various transcript formats
- **Instant Processing**: No upload time required

### URL Processing
- **Direct Links**: Works with direct video file URLs
- **YouTube Support**: Manual download required for YouTube videos
- **Error Handling**: Graceful fallback for unsupported formats

## AI-Generated Content

### Interactive Flashcards
- **Smart Parsing**: Automatic question/answer detection and correction
- **Flip Animation**: Smooth 3D card flip transitions
- **Progress Tracking**: Card counter and navigation controls
- **Content Validation**: Ensures proper Q&A formatting

### Multiple Choice Quizzes
- **Dynamic Generation**: 5 questions based on transcript content
- **Immediate Feedback**: Correct/incorrect answer indicators
- **Score Tracking**: Progress monitoring and results display
- **Content-Specific**: Questions derived directly from provided transcript

### Study Materials
- **Comprehensive Summaries**: Key points and main concepts
- **Structured Guides**: Organized study materials with clear sections
- **Markdown Rendering**: Clean formatting with proper headings
- **Content Filtering**: Removes formatting artifacts and numbering

## Technical Architecture

### Client-Side Implementation
- **Single HTML File**: Self-contained application with embedded CSS/JavaScript
- **No Backend Required**: Runs entirely in the browser
- **Local Storage**: Saves user preferences and progress
- **API Integration**: Direct OpenAI API calls for content generation

### Browser APIs Used
- **Web Audio API**: Audio file processing and playback
- **Web Speech API**: Text-to-speech and speech-to-text
- **File API**: Local file upload and processing
- **Fetch API**: OpenAI API communication

### Error Handling
- **Comprehensive Validation**: Input validation and error checking
- **Graceful Degradation**: Fallback options when features fail
- **User Feedback**: Clear error messages and guidance
- **Debug Tools**: Built-in testing and diagnostic functions

## Accessibility Compliance

### WCAG Guidelines
- **Color Contrast**: High contrast themes meet WCAG AA standards
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Support**: Semantic HTML and ARIA labels
- **Text Scaling**: Responsive font sizing up to 200%

### Universal Design for Learning (UDL)
- **Multiple Representations**: Visual, auditory, and textual content
- **Multiple Engagement**: Interactive elements and customizable themes
- **Multiple Expression**: Various ways to interact with content

## File Structure

```
├── complete_interactive_learning.html    # Main application file
├── README.md                             # Project documentation
├── FINAL_SUMMARY.md                      # Technical implementation details
├── Demo.mp4                              # Demonstration video
├── requirements.txt                      # Python dependencies (legacy)
└── *.mp4                                 # Sample educational content
```

## Development & Customization

### Adding New Features
- **Theme Customization**: Modify CSS variables in the stylesheet
- **API Integration**: Extend OpenAI prompts for new content types
- **Accessibility**: Add new accessibility controls and features
- **Content Types**: Implement additional learning material formats

### Browser Compatibility
- **Modern Browsers**: Chrome 80+, Firefox 75+, Safari 13+, Edge 80+
- **Mobile Support**: Responsive design for tablets and phones
- **Progressive Enhancement**: Core features work without JavaScript

## Troubleshooting

### Common Issues
- **API Key Errors**: Ensure valid OpenAI API key with sufficient credits
- **File Upload Issues**: Check file format and size limitations
- **Content Generation Failures**: Verify transcript has sufficient content (50+ characters)
- **Audio Playback Problems**: Check browser permissions and audio settings

### Debug Tools
- **Test API Connection**: Built-in API testing function
- **Clear AI Content**: Reset all generated materials
- **Debug Transcript**: View transcript content and metadata
- **Console Logging**: Detailed error messages in browser console

## Future Enhancements

### Planned Features
- **Offline Support**: Service worker for offline functionality
- **Export Options**: PDF and document export capabilities
- **Collaborative Features**: Shared study sessions and materials
- **Advanced Analytics**: Learning progress tracking and insights

### Scalability Considerations
- **API Optimization**: Batch processing and caching strategies
- **Performance**: Lazy loading and content optimization
- **Mobile Apps**: Native iOS and Android applications
- **Enterprise Features**: Multi-user support and admin controls

## Contributing

This project is designed for educational use and accessibility improvement. Contributions are welcome for:
- Accessibility enhancements
- New learning material types
- Performance optimizations
- Bug fixes and error handling
- Documentation improvements

## License

This project is developed for educational purposes and accessibility improvement. Please ensure compliance with OpenAI's API usage terms and applicable educational software regulations.

---

**Built for accessible education** 