<picture>
  <img alt="Shows a black Awesome Prompts Logo in light color mode and a white one in dark color mode." src="./static/awesome-prompts.png"  width="full">
</picture>

<br/>

A curated collection of effective prompts for Browser-Use. This repository aims to provide examples, templates, and best practices for crafting prompts that maximize the capabilities of Browser-Use agents. We will accept any prompts that are relevant and provide business value.

💡 See what others are building and share your projects in our [Discord](https://link.browser-use.com/discord)! Want Swag? Check out our [Merch store](https://browsermerch.com).

🌤️ You can the setup and try the prompts directly in the cloud! <b>[Try the cloud ☁︎](https://cloud.browser-use.com)</b>.

Thanks to [@metehan777](https://github.com/metehan777) for the initial collection of prompts.

## Table of Contents

1. [Introduction](#introduction)
2. [Web Research Prompts](#web-research-prompts)
3. [E-commerce Prompts](#e-commerce-prompts)
4. [Content Creation Prompts](#content-creation-prompts)
5. [Data Extraction Prompts](#data-extraction-prompts)
6. [Job Application Prompts](#job-application-prompts)
7. [Social Media Prompts](#social-media-prompts)
8. [Productivity Prompts](#productivity-prompts)
9. [Form Filling Prompts](#form-filling-prompts)
10. [Testing and QA Prompts](#testing-and-qa-prompts)
11. [Multi-Step Workflow Prompts](#multi-step-workflow-prompts)
12. [Prompt Engineering Best Practices](#prompt-engineering-best-practices)
13. [Contributing](#contributing)

## Web Research Prompts

### Comparative Research

```
Research and compare the pricing and key features of the top 3 competitors in the {industry} space: {competitor1}, {competitor2}, and {competitor3}.

For each competitor:
1. Navigate to their pricing page
2. Extract the pricing tiers and their costs
3. List the key features in each tier
4. Note any special offers or discounts currently available

Present the information in a structured format that makes it easy to compare the options.
```

### Academic Research

```
Find the latest research papers on {topic} published after {date}.

For each of the top 5 most cited papers:
1. Extract the title, authors, and publication date
2. Capture the abstract
3. Note the number of citations
4. Record the DOI or direct link to the paper

If you find papers behind paywalls, look for open-access alternatives or preprints when possible.
```

### News Summary

```
Research the latest developments regarding {topic} from at least 3 different reputable news sources.

For each source:
1. Navigate to their search function and find articles about the topic from the past week
2. Extract the headline, publication date, and author
3. Summarize the key points in 2-3 sentences

After gathering information, synthesize the findings into a comprehensive summary that notes any differences in reporting or perspective between the sources.
```

### Fact Verification

```
Verify the following claim: "{claim}".

1. Search for information about this claim from at least 3 different authoritative sources
2. For each source, extract:
   - The name and credibility of the source
   - Their stance on the claim (confirms, refutes, or partially supports)
   - Any evidence or data they provide

3. Determine if the original claim is:
   - Accurate
   - Partially accurate
   - Inaccurate
   - Unverifiable

Include direct quotes and links to support your assessment.
```

## E-commerce Prompts

### Product Price Comparison

```
Find the best price for {product} across major retailers including Amazon, Walmart, Best Buy, and Target.

For each retailer:
1. Navigate to their website and search for the exact product
2. Record the current price, original price if on sale, and any available discounts
3. Note shipping costs and estimated delivery time
4. Check if the product is in stock

Compile the information into a comparison table and identify the best overall deal considering price, shipping, and delivery time.
```

### Shopping Cart Automation

```
Add the following items to my shopping cart on {website}:

1. {item1} - {specifications1} - quantity: {quantity1}
2. {item2} - {specifications2} - quantity: {quantity2}
3. {item3} - {specifications3} - quantity: {quantity3}

For each item:
- If the exact item is unavailable, find the closest alternative
- If there are multiple options (size, color, etc.), select {preference}
- If the price is above {budget} for any item, look for a more affordable alternative

Once all items are in the cart:
- Apply coupon code: {coupon_code} if available
- Select the standard shipping option
- Proceed to checkout but stop before payment
```

### Deal Finder

```
Find the best current deals on {product_category} from {store1}, {store2}, and {store3}.

For each store:
1. Navigate to their deals/sale section
2. Filter for {product_category} items
3. Sort by discount percentage (highest first) if possible
4. Record the top 5 deals, including:
   - Product name
   - Original price
   - Current price
   - Discount percentage
   - Link to the product

For each product, verify customer ratings are above 4 stars if available. Exclude any deals that expire within 24 hours.
```

### Product Research

```
Research {product} and help me make an informed purchase decision.

1. Find at least 3 different models/brands that match these criteria:
   - Price range: {min_price} to {max_price}
   - Must have features: {required_features}
   - Preferred but optional: {optional_features}

2. For each product, find:
   - Detailed specifications
   - At least 2 expert reviews
   - Summary of customer reviews (pros and cons)
   - Warranty information

3. Check availability at {preferred_retailer} and {alternate_retailer}

4. Create a comparison highlighting the key differences in features, performance, and value.
```

## Content Creation Prompts

### Blog Post Draft

```
Go to Google Docs and create a new document. Write a well-structured blog post about {topic} following these steps:

1. Research the top 5 articles on Google about {topic} to understand current perspectives
2. Draft a compelling headline that includes the primary keyword
3. Write an introduction that highlights the key problem or opportunity
4. Create 3-5 main sections with appropriate subheadings
5. Include bullet points or numbered lists where appropriate
6. Add a conclusion with a clear call-to-action
7. Suggest 2-3 relevant images that could be included (with placeholder descriptions)

The blog post should be approximately 1000-1200 words and written in a {formal/conversational/educational} tone.
```

### Social Media Content Calendar

```
Go to Google Sheets and create a content calendar for {brand} for the next two weeks with daily posts for {social_media_platform1} and {social_media_platform2}.

For each day:
1. Create a theme or topic aligned with {brand}'s industry
2. Draft the main copy for each post (appropriate length for each platform)
3. Suggest hashtags (3-5 per post)
4. Describe the type of image or video that should accompany the post
5. Note the ideal posting time based on platform best practices

Make sure to incorporate trending topics related to {industry} and include at least one post about {upcoming_event/holiday}.
```

### Email Newsletter

```
Go to {email_platform} and draft a newsletter for {business} with the following sections:

1. Compelling subject line with an open rate of at least 25%
2. Brief personalized greeting
3. Main feature article about {current_topic} (250-300 words)
4. Secondary content section highlighting {product/service/news} (150 words)
5. "What's New" section featuring {recent_development} (100 words)
6. Call-to-action section promoting {offer/event}
7. Footer with social media links and unsubscribe option

The newsletter should maintain {brand}'s voice, which is {brand_voice_description}. Include appropriate heading styles, bullet points, and suggested image placements.
```

### Presentation Creation

```
Go to Google Slides and create a professional presentation about {topic} for {audience_type}.

The presentation should include:
1. Title slide with an engaging headline
2. Agenda/overview slide
3. Problem statement (1-2 slides)
4. Key data points and statistics (2-3 slides)
5. Solution or main insights (3-4 slides)
6. Implementation steps or recommendations (2-3 slides)
7. Conclusion slide with key takeaways
8. Q&A placeholder slide
9. Contact information slide

Use a professional template with {brand_colors}. Each slide should follow the 6x6 rule (maximum 6 bullet points, maximum 6 words per bullet). Include speaker notes with expanded information for each slide.
```

## Data Extraction Prompts

### Tabular Data Extraction

```
Extract structured data from {website} about {data_category}.

1. Navigate to {specific_page_or_search_query}
2. Identify the table or structured data containing information about {data_points}
3. Extract all rows and columns while preserving the relationship between data points
4. If pagination exists, navigate through at least the first 3 pages and extract all data
5. If filters are available, apply {filter_criteria} before extraction

Format the extracted data in a CSV-compatible format with appropriate headers. If any data points are missing, mark them as "N/A" rather than leaving them blank.
```

### Contact Information Extraction

```
Extract contact information for {company_name} from their official website and any other authoritative sources.

Find and record:
1. Main office address(es)
2. Phone number(s) with department labels if available
3. Email address(es) with department labels if available
4. Names and positions of key executives/leadership team
5. Social media profiles
6. Customer support contact methods and hours

Verify the information across multiple pages of their website and cross-reference with their LinkedIn and Google Business profiles when possible.
```

### Product Specifications Extraction

```
Extract detailed specifications for {product} from {manufacturer_website} and at least two retailer websites.

For each specification category:
1. Technical specifications (dimensions, weight, materials, etc.)
2. Performance specifications (speed, capacity, efficiency, etc.)
3. Compatibility information
4. Power/energy requirements
5. Warranty details
6. Included accessories or components
7. System requirements (if applicable)

Note any discrepancies between the manufacturer's specifications and those listed by retailers. Format the information in a structured, easily readable format.
```

### Competitor Analysis Extraction

```
Perform a comprehensive competitor analysis for {company_name} by extracting information about their top 5 competitors.

For each competitor:
1. Navigate to their official website
2. Extract their mission statement or about us information
3. Identify their key products/services and unique selling propositions
4. Find pricing information if publicly available
5. Note their target audience/market segments
6. Extract recent news or press releases from the past 3 months
7. Identify their marketing strategies based on website content

Compile the information in a structured format that allows for easy comparison across all competitors.
```

## Job Application Prompts

### Job Search and Application

```
Help me find and apply to {job_title} positions in the {industry} industry.

1. Go to {job_board1}, {job_board2}, and {job_board3}
2. Search for jobs matching these criteria:
   - Job title: {job_title} or similar titles
   - Location: {location} (include remote options if applicable)
   - Experience level: {experience_level}
   - Salary range: {salary_range} (if filterable)

3. For each promising job posting:
   - Extract the job title, company, location, and posting date
   - Record the key responsibilities and requirements
   - Note application deadline and process
   - Save the direct application link

4. After finding at least 5 suitable positions, help me prepare an application for the most promising opportunity by:
   - Reading my resume (uploaded as {resume_filename})
   - Tailoring a cover letter specifically for this position
   - Suggesting resume adjustments to better align with the job requirements
```

### LinkedIn Profile Optimization

```
Help me optimize my LinkedIn profile to improve my chances of getting noticed for {target_job_title} roles.

1. Navigate to LinkedIn and log in with my credentials
2. Go to my profile page
3. Analyze each section of my profile and suggest improvements:
   - Profile photo and banner
   - Headline (create one that includes key terms for my target role)
   - About section (craft a compelling summary highlighting relevant skills)
   - Experience section (enhance job descriptions with accomplishments and metrics)
   - Skills section (suggest the top 10 skills I should list based on {target_job_title})
   - Education and certifications
   - Recommendations and endorsements

4. Research profiles of 3 successful professionals in similar roles and identify elements I should incorporate
5. Suggest 5 LinkedIn groups I should join related to {industry}
6. Draft 3 potential posts I could share to demonstrate expertise in my field
```

### Interview Preparation

```
Help me prepare for an upcoming job interview for a {job_title} position at {company_name}.

1. Research {company_name}:
   - Navigate to their official website, LinkedIn, Glassdoor, and recent news
   - Extract information about their mission, values, products/services
   - Identify recent company developments, achievements, or challenges
   - Research their work culture and employee reviews

2. Prepare answers for likely interview questions:
   - Create responses for 5 common general interview questions
   - Develop answers for 7 role-specific technical questions for {job_title}
   - Craft responses for 3 behavioral questions using the STAR method
   - Prepare 2 stories that demonstrate my experience with {key_skill1} and {key_skill2}

3. Develop 5 insightful questions I can ask the interviewer about the role and company

4. Find information about typical salary ranges for this position in this location and industry to prepare for compensation discussions.
```

### Resume Tailoring

```
Help me tailor my resume for a {job_title} position at {company_name}.

1. First, find and analyze the job description from the company's careers page or job posting
2. Extract:
   - Key responsibilities
   - Required skills and qualifications
   - Preferred qualifications
   - Company values and keywords

3. Read my current resume (uploaded as {resume_filename})

4. For each section of my resume, suggest specific modifications:
   - Professional summary/objective statement tailored to this role
   - Work experience bullet points that highlight relevant accomplishments
   - Skills section adjustments to prioritize matching skills
   - Additional sections to add or remove

5. Identify ATS (Applicant Tracking System) optimization opportunities by suggesting:
   - Keywords from the job description to include
   - Formatting improvements for better ATS readability
   - Industry-specific terminology to incorporate

The goal is to create a highly targeted version of my resume that clearly shows I'm an excellent match for this specific position.
```

## Social Media Prompts

### Content Engagement

```
Engage with content on {social_media_platform} related to {topic} to increase my profile visibility in that space.

1. Search for the top 10 most engaging recent posts about {topic}
2. For each post:
   - Read the content and comments to understand the discussion
   - Craft a thoughtful comment that adds value to the conversation
   - Include relevant hashtags when appropriate
   - Ask an insightful question when possible to encourage response

3. Identify 5 thought leaders in this space and:
   - Follow their accounts
   - Engage with their most recent relevant post
   - Share one of their valuable posts with a brief comment explaining why it's insightful

4. Find and join 2-3 relevant groups or communities focused on {topic}

All engagement should be professional, authentic, and aligned with my brand voice as {personal_brand_description}.
```

### Scheduled Posting

```
Create and schedule social media posts for {business_name} on {platform1} and {platform2} for the upcoming week.

For each platform, create:
1. Three educational posts about {industry_topic}
2. Two promotional posts about {product/service}
3. One user-generated content share or testimonial highlight
4. One trending topic or industry news commentary
5. One behind-the-scenes or company culture post

For each post:
- Draft the main copy tailored to the platform's optimal length
- Create a relevant call-to-action
- Suggest 3-5 appropriate hashtags
- Describe the ideal image or video to accompany the post
- Recommend the optimal posting time based on our audience analytics

Use our brand voice guide which emphasizes {tone_description} and avoids {prohibited_content}.
```

### Trend-Aligned Brand Collaboration Pitch

```
Objective: Craft a personalized outreach message to {brand_name} proposing a promotion partnership focused on their latest {product_line/trend}, leveraging my influencer profile strengths.  
my influencer profile is : {your_profile}
Step 1: Research & Alignment  
1. Analyze {brand_name}'s:  
   - Recent product launches/trends (last 3 months)  
   - Current marketing campaigns/hashtags  
   - Competitor collaborations in {industry}  

2. Review my influencer profile:  
   - Audience demographics: {age, gender, location}  
   - Top-performing content formats: {e.g., reels, unboxings, tutorials}  
   - Engagement metrics: {avg. rate%, follower count}  
   - Past successful collabs: {brand examples + results}  

Step 2: Customized Pitch Structure  
Subject Line:  
"Collaboration Idea: [Creative Hook Tied to Their Trend]"  

Body Template:  
1. Opener:  
   - Praise their innovation: *"Loved your new {product/trend}—especially how it tackles {specific audience pain point}!"*  

2. Strategic Fit:  
   - *"My {niche} audience aligns perfectly with your target {demographic}—see attached profile highlights."*  
   - Data point: *"My last {similar_product} post drove {X} conversions for {competitor}."*  

3. Proposal:  
   - Content format: *"{Video style} showcasing {trend} through {unique angle}"*  
   - Timeline: *"Launch during {their_campaign/seasonal moment}"*  
   - Callout: *"I can amplify your {hashtag/challenge} with authentic UGC."*  

4. CTA:  
   - *"Let’s discuss goals—I’ve attached a media kit with rates and examples."*  

Step 3: Deliverables  
- Draft email + LinkedIn DM version  
- 3 hook options for subject lines  
- Performance screenshots to attach  
- Follow-up schedule (3-5-7 day sequence)  
```

### Social Listening and Response

```
Conduct social listening for {brand_name} across {platform1}, {platform2}, and {platform3} and help craft appropriate responses.

1. Search for recent mentions of {brand_name} and related terms {related_term1}, {related_term2}
2. Categorize mentions as:
   - Positive feedback
   - Customer service issues
   - Product questions
   - General mentions
   - Competitor comparisons

3. For each category, identify the 3-5 most important conversations based on:
   - User influence/follower count
   - Engagement level on the post
   - Sentiment intensity
   - Potential impact on brand reputation

4. For each identified conversation, draft an appropriate response following our response guidelines:
   - Positive feedback: Thank them and reinforce brand relationship
   - Customer service: Acknowledge issue, express empathy, move to private channel
   - Product questions: Provide accurate information with links to resources
   - General mentions: Engage authentically in alignment with brand voice
   - Competitor comparisons: Highlight differentiators without disparaging competitors
```

### Influencer Research

```
Research potential influencers for a partnership with {brand_name} to promote {product/service}.

1. On {platform1} and {platform2}, find 10 influencers who:
   - Have between {min_followers} and {max_followers} followers
   - Create content related to {niche/industry}
   - Have an audience demographic matching {target_audience}
   - Have an engagement rate of at least {min_engagement_rate}%

2. For each influencer, analyze:
   - Content quality and brand alignment
   - Posting frequency and consistency
   - Previous brand partnerships
   - Audience sentiment in comments
   - Any potential red flags or controversies

3. Create a ranked shortlist of the top 5 candidates with:
   - Profile links
   - Key audience demographics
   - Estimated reach and engagement metrics
   - Suggested partnership approach (sponsored post, takeover, affiliate, etc.)
   - Estimated appropriate compensation range based on industry standards
```

## Productivity Prompts

### Calendar Management

```
Optimize my work calendar for the upcoming week to maximize productivity and work-life balance.

1. Go to Google Calendar (or another calendar tool) and analyze my current schedule
2. Identify and flag:
   - Meeting overlaps or conflicts
   - Days with back-to-back meetings without breaks
   - Schedule gaps that could be utilized more effectively
   - Long meetings that could potentially be shortened

3. Suggest specific improvements:
   - Group similar types of meetings (e.g., one-on-ones, project reviews) on the same day
   - Block focused work time for {priority_project}
   - Add buffer time between meetings (15 minutes recommended)
   - Schedule dedicated time for email/message processing (twice daily recommended)
   - Add self-care blocks for {preferred_activity}

4. Create calendar invites for the suggested changes or send me a proposal I can implement
```

### Email Management

```
Help me achieve inbox zero by processing my email backlog efficiently.

1. Go to my email client and focus on emails from the past {time_period}
2. For each email, apply the following workflow:
   - Delete: Obvious spam or irrelevant messages
   - Archive: FYI emails that require no action
   - Respond: Quick replies that take less than 2 minutes
   - Flag for follow-up: Emails requiring more thought or action
   - Create task: Convert action items into tasks in {task_system}

3. For emails requiring responses:
   - Draft concise replies focusing on clear next actions
   - Use templates where appropriate for similar requests
   - Suggest polite ways to decline low-priority requests

4. Organize remaining emails by:
   - Creating appropriate folders/labels for different projects or clients
   - Setting up filters for recurring email types
   - Suggesting email subscriptions that could be unsubscribed

5. Recommend sustainable email habits to maintain inbox zero going forward
```

### Task Prioritization

```
Help me prioritize my tasks and create an effective work plan for the next {time_period}.

1. Navigate to my task management system ({task_system})
2. Extract all current tasks and categorize them by:
   - Project
   - Deadline
   - Estimated time required
   - Dependency on others
   - Strategic importance

3. Apply the Eisenhower Matrix to sort tasks into:
   - Urgent and important (do immediately)
   - Important but not urgent (schedule time)
   - Urgent but not important (delegate if possible)
   - Neither urgent nor important (eliminate or defer)

4. Create a specific action plan with:
   - Top 3 priorities for today
   - Scheduled blocks for focused work on important tasks
   - Suggested tasks to delegate with draft delegation messages
   - Tasks that can be batched together for efficiency
   - Tasks that can be eliminated or postponed with minimal impact

5. Set up a follow-up system to track progress on key deliverables
```

### Information Organization

```
Help me organize my digital information and files to create a more efficient system.

1. Assess my current file organization on {storage_platform} (Google Drive, Dropbox, etc.)
2. Analyze the structure for:
   - Inconsistent naming conventions
   - Duplicate files
   - Outdated documents that can be archived
   - Files without clear categorization

3. Propose an improved organizational system with:
   - A logical folder hierarchy based on {preferred_structure} (project-based, client-based, etc.)
   - Consistent file naming conventions
   - Permission settings recommendations for shared files
   - Archiving strategy for completed projects

4. Create the suggested folder structure
5. Move files into the appropriate locations (starting with the most frequently accessed)
6. Document the new system with guidelines for maintaining it going forward

7. Suggest tools or automation that could help maintain this system
```

## Form Filling Prompts

### Account Registration

```
Complete the registration process for a new account on {website}.

1. Navigate to {website} and locate the sign-up or registration page
2. Fill out the registration form with the following information:
   - Email: {email}
   - Username: {preferred_username} (if unavailable, try variations like {alternative1}, {alternative2})
   - Password: {password} (ensure it meets the site's security requirements)
   - Name: {name}
   - Address: {address}
   - Phone: {phone}
   - Other required fields: {additional_info}

3. If presented with optional fields about preferences or settings:
   - Select {preferences}
   - Opt out of marketing communications unless specifically requested
   - Review privacy settings and set them according to {privacy_preference}

4. Complete any verification steps like:
   - Email verification (check {email} for confirmation link)
   - Phone verification (report the code sent to {phone})
   - CAPTCHA or other human verification

5. Review the terms of service highlight any concerning clauses before accepting
```

### Comprehensive Profile Setup

```
Set up a complete profile on {platform} to maximize its effectiveness for {goal}.

1. Log in to {platform} using the provided credentials
2. Navigate to the profile or account settings section
3. Upload the profile picture from {image_path}
4. Complete each section of the profile with the following information:
   - Personal/Professional Bio: {bio_text}
   - Experience: {experience_details}
   - Education: {education_details}
   - Skills: {skills_list}
   - Interests: {interests_list}
   - Contact information: {contact_details}
   - Social media links: {social_media_accounts}

5. For platform-specific sections (like {platform_specific_section}), complete using {specific_content}
6. Set appropriate privacy settings according to {privacy_preferences}
7. Review profile completeness indicators and address any suggestions for improvement
8. Test how the profile appears to others using any "view as" functionality

Ensure all information is accurate, professional, and aligned with the objective of {goal}.
```

### Tax Form Completion

```
Help me complete my {tax_form_type} for {tax_year}.

1. Navigate to {tax_website} and log in with the provided credentials
2. Begin a new {tax_form_type} for {tax_year}
3. For each section, enter the appropriate information from my documents:
   - Personal information from {personal_doc}
   - Income information from {w2_docs}, {1099_docs}
   - Deduction information from {deduction_docs}
   - Credit information from {credit_docs}
   - Investment information from {investment_docs}

4. For any sections where information is unclear:
   - Flag the section for my review
   - Explain what additional information is needed
   - Suggest potential sources for the information

5. Before submitting:
   - Review all entries for accuracy
   - Compare key figures with last year's return for significant discrepancies
   - Calculate the estimated refund or amount owed
   - Save the return as a draft for my final review

Do not submit the final return, but prepare it to the point where it is ready for my final verification and submission.
```

### Survey Completion

```
Complete the customer feedback survey for {product/service} from {company}.

1. Navigate to the survey link: {survey_link}
2. For rating questions (1-5 or 1-10 scales):
   - Overall satisfaction: {overall_rating}
   - Product quality: {quality_rating}
   - Customer service: {service_rating}
   - Value for money: {value_rating}
   - Likelihood to recommend: {recommendation_rating}

3. For multiple-choice questions, select options that align with:
   - Frequency of use: {usage_frequency}
   - Primary purpose: {usage_purpose}
   - Features used most often: {key_features}

4. For open-ended questions, write thoughtful responses about:
   - What I liked most: {positive_aspects}
   - What could be improved: {improvement_suggestions}
   - Additional features desired: {desired_features}

5. Demographic questions (if asked):
   - Fill in basic information without sharing unnecessarily sensitive details
   - Skip optional demographic questions unless specifically instructed to complete them

Complete the survey honestly but constructively, providing feedback that would be helpful for product improvement.
```

## Testing and QA Prompts

### Website Functionality Testing

```
Perform a comprehensive functionality test of {website} focusing on the {specific_feature} and core user journeys.

Test the following user flows:
1. User registration and login process
   - Create a new account with test credentials
   - Verify email confirmation process
   - Log out and log back in
   - Test password reset functionality

2. {specific_feature} functionality
   - Test all UI elements (buttons, forms, dropdowns)
   - Verify data entry and validation
   - Test error handling and messaging
   - Check performance under various conditions

3. Critical user journeys
   - {user_journey1} (e.g., product search to checkout)
   - {user_journey2} (e.g., account settings update)
   - {user_journey3} (e.g., content submission)

4. Cross-browser compatibility
   - Test core functionality on Chrome, Firefox, and Safari
   - Document any rendering or functionality differences

For each test, document:
- Test case description
- Expected behavior
- Actual behavior
- Screenshots of issues encountered
- Severity rating (Critical, High, Medium, Low)
```

### Responsive Design Testing

```
Test the responsive design of {website} across various device types and screen sizes.

1. Test the following key pages:
   - Homepage
   - {page1} (e.g., product listing)
   - {page2} (e.g., product detail)
   - {page3} (e.g., checkout)
   - {page4} (e.g., account settings)

2. For each page, test the following screen sizes and orientations:
   - Mobile: 320px, 375px, 414px (portrait and landscape)
   - Tablet: 768px, 1024px (portrait and landscape)
   - Desktop: 1366px, 1920px

3. For each combination, evaluate:
   - Content visibility and readability
   - Navigation usability
   - Image and media scaling
   - Form functionality
   - Touch targets and interactive elements
   - Load time and performance

4. Test specific responsive features:
   - Hamburger menu functionality on mobile
   - Collapsible sections
   - Image carousels/sliders
   - Tables or complex data representations
   - Modal windows and popups

Document all issues with screenshots, device information, and recommended fixes. Prioritize issues based on severity and frequency of user encounter.
```

### User Registration Flow Testing

```
Test the entire user registration flow on {website} to identify any usability issues or bugs.

1. Begin by navigating to the site's homepage and finding the registration option
2. Test the following registration methods:
   - Email registration
   - Google/social media account registration (if available)
   - Phone number registration (if available)

3. For email registration, test:
   - Form validation for each field
   - Password strength requirements
   - Email verification process
   - "Already registered" error handling

4. Document the following for each step:
   - Field requirements and validations
   - Error messages (clarity and helpfulness)
   - Number of steps in the process
   - Time taken to complete each step

5. Test edge cases:
   - Using an email that's already registered
   - Using invalid formats for fields
   - Abandoning the process mid-way and returning
   - Registering from different browsers or devices

6. After successful registration, verify:
   - Welcome email receipt and content
   - Initial account state and settings
   - Any onboarding processes or tutorials
   - Logout and login functionality with the new account

Provide a detailed report with screenshots of any issues found, along with severity ratings and suggestions for improvement.
```

### Accessibility Testing

```
Conduct an accessibility test of {website} to identify issues that may impact users with disabilities.

1. Test keyboard navigation:
   - Tab through all interactive elements on key pages
   - Verify visible focus indicators
   - Test all functionality without using a mouse
   - Check for keyboard traps or inaccessible elements

2. Test screen reader compatibility:
   - Enable VoiceOver (Mac) or NVDA (Windows)
   - Navigate through key pages and verify all content is announced
   - Check for appropriate alt text on images
   - Verify form fields have proper labels
   - Test dynamic content updates

3. Test color contrast and visual presentation:
   - Check text contrast against backgrounds
   - Verify information is not conveyed by color alone
   - Test the site at 200% zoom
   - Verify the site works in high contrast mode

4. Test form and interactive elements:
   - Verify clear error messages
   - Check for appropriate input validation
   - Test timeout warnings and session management
   - Verify multimedia has captions or transcripts

5. Check against WCAG 2.1 AA standards:
   - Verify semantic HTML structure
   - Check for proper heading hierarchy
   - Test ARIA implementations
   - Verify appropriate landmark regions

Document all issues with screenshots, steps to reproduce, and references to relevant WCAG criteria.
```

## Multi-Step Workflow Prompts

### Research and Report Generation

```
Create a comprehensive market research report on {industry} trends and competitive landscape.

1. Research Phase:
   - Search for industry reports from sources like Statista, IBISWorld, and Gartner
   - Find recent news articles about {industry} from the past 6 months
   - Identify the top 5 companies in this space and gather key metrics
   - Locate market size estimates and growth projections
   - Find information about emerging technologies or disruptions in this sector

2. Data Organization Phase:
   - Create a Google Sheet to compile numerical data and key statistics
   - Organize company profiles with strengths, weaknesses, and unique offerings
   - Track market share percentages and changes over time
   - Compile consumer trend data and demographic information

3. Analysis Phase:
   - Identify 3-5 key trends shaping the industry
   - Analyze competitive positioning of major players
   - Evaluate market opportunities and threats
   - Examine regulatory factors affecting the industry
   - Assess technological impacts on future growth

4. Report Creation Phase:
   - Create a Google Doc with a professional structure including:
     - Executive summary
     - Industry overview with market size and growth rates
     - Competitive landscape analysis
     - Detailed trend analysis with supporting data
     - Future outlook and strategic recommendations
     - References and methodology section
   - Add appropriate charts and tables from your research
   - Format the document professionally with consistent styling

The final report should be 10-15 pages, include proper citations, and be suitable for presentation to executive stakeholders.
```

### Event Planning Workflow

```
Plan a {event_type} for {number_of_attendees} people on {date} with a budget of {budget}.

1. Venue Research Phase:
   - Search for appropriate venues in {location} that can accommodate {number_of_attendees}
   - Compare at least 5 options based on:
     - Availability on {date}
     - Cost and what's included in the package
     - Amenities and services
     - Reviews and ratings
     - Distance from {central_location}
   - Create a comparison spreadsheet of options

2. Vendor Selection Phase:
   - Research and compare options for:
     - Catering ({food_preferences})
     - Photography/videography
     - Entertainment ({entertainment_preferences})
     - Decorations
     - Other necessary services
   - Get price quotes and availability for the top 2 choices in each category

3. Budget Allocation Phase:
   - Create a detailed budget spreadsheet with categories:
     - Venue and space rental
     - Food and beverage
     - Entertainment
     - Decorations and supplies
     - Staffing
     - Marketing (if applicable)
     - Contingency (10% recommended)
   - Adjust allocations to stay within {budget}

4. Timeline Creation Phase:
   - Create a planning timeline with milestones and deadlines
   - Develop a detailed day-of schedule
   - Create a task list with assignments and due dates

5. Invitation and Communication Plan:
   - Design an invitation template
   - Set up a communication plan for attendees
   - Create an RSVP tracking system

Compile all this information into a comprehensive event plan document with relevant links, contact information, and action items.
```

### Website Migration Workflow

```
Create a comprehensive plan for migrating {website} from {current_platform} to {new_platform}.

1. Content Audit Phase:
   - Crawl the existing website to inventory all pages
   - Identify and catalog all:
     - Pages and posts
     - Media files (images, videos, documents)
     - Forms and interactive elements
     - Custom functionality and integrations
     - SEO elements (meta descriptions, alt text, URLs)
   - Create a content mapping spreadsheet

2. Technical Planning Phase:
   - Research and document the migration process for:
     - Database transfer
     - User account migration
     - URL structure and redirects
     - Theme and design elements
     - Third-party integrations
     - Performance optimization
   - Create a technical requirements document

3. Timeline and Task Assignment Phase:
   - Create a detailed migration timeline with phases:
     - Pre-migration preparation
     - Development environment setup
     - Content transfer
     - Design implementation
     - Testing
     - Launch
     - Post-launch monitoring
   - Define dependencies and critical path
   - Assign responsibilities for each task

4. Testing Plan Development:
   - Create test cases for:
     - Content integrity
     - Functionality
     - Performance
     - Mobile responsiveness
     - SEO elements
     - User accounts and permissions
   - Develop a QA checklist

5. Launch Strategy:
   - Create a detailed launch day plan
   - Develop a rollback plan in case of issues
   - Design a communication plan for users/customers
   - Create a post-launch monitoring schedule

Compile all elements into a master migration plan document with clear phases, responsibilities, and success criteria.
```

### Product Launch Campaign

```
Design and plan a comprehensive product launch campaign for {product_name} targeting {target_audience}.

1. Market Research Phase:
   - Research the target audience demographics and preferences
   - Analyze competitor product launches in the same space
   - Identify key influencers and media outlets in this market
   - Determine the most effective channels for reaching the audience
   - Research industry events or timing considerations

2. Campaign Strategy Development:
   - Create campaign objectives and key performance indicators
   - Develop the central value proposition and messaging
   - Design a campaign theme and creative concept
   - Establish the campaign timeline with key milestones
   - Allocate the budget across different activities

3. Content Creation Plan:
   - Design the product landing page structure
   - Create a content calendar for social media
   - Draft press release and media kit materials
   - Develop email marketing sequence for different segments
   - Plan video content and promotional materials

4. Launch Execution Plan:
   - Create a detailed launch day checklist
   - Develop a social media posting schedule
   - Plan influencer outreach with personalized pitches
   - Schedule email campaign deployment
   - Coordinate PR activities and media outreach

5. Post-Launch Measurement:
   - Set up analytics tracking for all channels
   - Create a dashboard for monitoring KPIs
   - Design a feedback collection mechanism
   - Plan for rapid response to issues or opportunities
   - Schedule campaign performance review meetings

Compile all elements into a master launch plan document with timelines, responsibilities, and budget allocations for each component.
```

## Prompt Engineering Best Practices

### Structure

- **Be specific about the goal**: Clearly state what you want to accomplish
- **Break complex tasks into steps**: Use numbered lists for multi-step processes
- **Include format specifications**: Mention desired output formats and structures
- **Provide context**: Include relevant background information the agent needs
- **Set constraints**: Specify any limitations or requirements the agent should follow

### Clarity

- **Use precise language**: Avoid ambiguity and vague instructions
- **Specify parameters**: Include exact values, ranges, or criteria
- **Clarify expectations**: Explain what success looks like
- **Include examples**: Provide examples of desired outputs when helpful
- **Define terminology**: Explain industry-specific or technical terms

### Adaptability

- **Include fallback options**: Provide alternatives if the primary approach fails
- **Specify error handling**: Explain how to deal with potential issues
- **Allow for iteration**: Build in opportunities for refinement
- **Request verification**: Ask the agent to verify critical information
- **Include decision points**: Define how choices should be made when alternatives exist

### Efficiency

- **Prioritize tasks**: Indicate which aspects are most important
- **Set time or resource limits**: Specify constraints on depth or breadth
- **Focus on value-add activities**: Emphasize where the agent can provide the most value
- **Minimize unnecessary steps**: Avoid redundant or low-value activities
- **Batch similar operations**: Group related tasks for efficiency

## Contributing

Contributions to this repository are welcome! Please follow these guidelines:

1. **Format**: Use the established template format for consistency
2. **Categories**: Add to existing categories or propose new ones with at least 3 examples
3. **Quality**: Ensure prompts are specific, actionable, and well-structured
4. **Testing**: Verify that prompts work as expected with Browser-Use before submitting
5. **Descriptions**: Include a brief description of what the prompt accomplishes + a gif or screenshot if possible

To contribute:

1. Fork the repository
2. Create a feature branch
3. Add your prompts following the established format
4. Submit a pull request with a clear description of your additions

By sharing effective prompts, you help the entire Browser-Use community achieve better results!
