---
layout: default
title: "Membership Info"
---

{% include page-header.html %}

OWRPC is a Home Office approved club with approximately 80 members and is affiliated to the National Rifle Association (NRA). The Club is managed by a committee elected by the members at the Annual General Meeting.

A number of members are qualified NRA Range Conducting Officers, and the Club is licensed to use MoD Gallery Ranges. The Club meets on one of these ranges every month, and competitions for practical and classic rifles are held every year.

In addition to the regular programme of shooting activities, the Club organises visits to places of interest such as military museums and firepower demonstrations.

Members pay £2 for use of the indoor range. Fullbore shoots are £20 for static targets or £30 for electric targets (fall when hit).

PLEASE NOTE: The minimum age for members is 14, and anyone under 18 must be accompanied at all times by a parent or guardian.

As a new member of the OWRPC you will serve a three month probationary period. During this time you will be given a safety briefing and you will then be allowed to use club firearms under the supervision of experienced members. This will help you to decide where your interests lie and what shooting disciplines you want to pursue.

At the end of the probationary period, and subject to your satisfactory attitude, conduct and completion of our NRA-approved training scheme, the Club will assist and support you in your application for a Firearms Certificate (FAC).

When your FAC arrives you may then purchase your first sporting firearm! Club members own a wide variety of target, sporting and service rifles, black powder rifles and pistols, and long barrelled revolvers. If you need any help or guidance in choosing, using and maintaining your firearms the other Club members will be happy to oblige.

Many members reload their own ammunition to increase accuracy and reduce cost, and will be pleased to advise you should you decide to follow suit.

For further information on joining the Club, arranging a visit or submitting an application, please contact us. Please note that, unless you already hold an FAC, you must join the Club before you can shoot with us.

<div class="card">
  <div class="card-header">
    <div class="row align-items-center">
      <div class="col">
        <h4 class="card-header-title">Downloads</h4>
      </div>
    </div>
  </div>
  <div class="card-body">
    <ul class="list-group list-group-lg list-group-flush list my--4">
      {% for item in site.data.membership_docs.files %}
      <li class="list-group-item px-0">
        <div class="row align-items-center">
          <div class="col-auto">
            <div class="avatar avatar-lg">
              <span class="avatar-title rounded bg-white text-secondary">
                <span class="fe fe-file-text"></span>
              </span>
            </div>
          </div>
          <div class="col ml--2">
            <h4 class="card-title mb-1 name"><a href="{{ item.path }}">{{ item.title }}</a></h4>
            <p class="card-text small text-muted mb-1">{{ item.size }} ({{ item.type }})</p>
            <p class="card-text small text-muted">{{ item.description }}</p>
          </div>
          <div class="col-auto">
            <a href="{{ item.path }}" class="btn btn-sm btn-white d-none d-md-inline-block">View in Browser</a>
          </div>
          <div class="col-auto">
            <a href="{{ item.path }}" class="btn btn-sm btn-primary d-none d-md-inline-block" download>Download</a>
          </div>
        </div>
      </li>
      {% endfor %}
    </ul>
  </div>
</div>
