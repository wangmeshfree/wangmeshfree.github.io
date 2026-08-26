---
# Leave the homepage title empty to use the site title
title: multi-media
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: ""
      text: |
        <div class="course-accordion media-accordion">
          <details class="course-item" open>
            <summary>Landslide by RKPM meshfree method</summary>
            <div class="course-content">
              {{< video src="landslide.mp4" poster="multi-media-posters/landslide.png" controls="yes" >}}
            </div>
          </details>

          <details class="course-item" open>
            <summary>Penetration by RKPM meshfree method</summary>
            <div class="course-content">
              {{< video src="penetration.mp4" poster="multi-media-posters/penetration.png" controls="yes" >}}
            </div>
          </details>

          <details class="course-item" open>
            <summary>A twisted soda can by RKPM meshfree method</summary>
            <div class="course-content">
              {{< video src="soda.mp4" poster="multi-media-posters/soda.png" controls="yes" >}}
            </div>
          </details>

          <details class="course-item" open>
            <summary>Shell-based spinodal structure by RKPM meshfree method</summary>
            <div class="course-content">
              {{< video src="spin.mp4" poster="multi-media-posters/spinodal.png" controls="yes" >}}
            </div>
          </details>

          <details class="course-item" open>
            <summary>Concrete printing by RKPM meshfree method</summary>
            <div class="course-content">
              {{< video src="concrete.mp4" poster="multi-media-posters/concrete.png" controls="yes" >}}
            </div>
          </details>
        </div>

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: video-narrow
---